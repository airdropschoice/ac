<script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        $('a[href*="#"]').on('click', function(e) {
            const target = $($(this).attr('href'));
            if (target.length) {
                e.preventDefault();
                $('html, body').animate(
                    {
                        scrollTop: target.offset().top - 80,
                    },
                    500,
                    'linear'
                );
            }
        });

        // Form submission
        document.getElementById('subscribe-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = document.getElementById('email').value;
            alert(Thank you for subscribing with ${email}! You'll receive airdrop alerts soon.);
            this.reset();
        });

        // Scroll animations
        function animateOnScroll() {
            const elements = document.querySelectorAll('.card-hover, .gradient-text, .floating');
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.3;
                
                if (elementPosition < screenPosition) {
                    element.classList.add('animate__animated', 'animate__fadeInUp');
                }
            });
        }

        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
    </script>

</body></html>
