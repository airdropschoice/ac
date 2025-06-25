<!DOCTYPE html>
<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airdrop Hunter - Web3 Airdrop Opportunities</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.slim.min.js" integrity="sha256-kmHvs0B+OpCW5GVHUNjv9rOmY0IvSIRcf7zGUDTDQM8=" crossorigin="anonymous"></script>
    <style>
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        .floating { animation: float 3s ease-in-out infinite; }
        .pulse { animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite; }
        .gradient-text {
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }
        .section {
            scroll-margin-top: 80px;
        }
        .social-icon {
            transition: all 0.3s ease;
        }
        .social-icon:hover {
            transform: scale(1.2);
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
    </style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  document.body.addEventListener('click', function(event) {
    let anchor = event.target.closest('a');
    if (anchor) {
      const href = anchor.getAttribute('href');
      if (href && href.startsWith('#')) {
        event.preventDefault(); // Prevent default for all # links
        
        if (href.length > 1) {
          try {
            const targetId = decodeURIComponent(href.substring(1));
            const element = document.getElementById(targetId);
            if (element) {
              event.stopPropagation();
              element.scrollIntoView({ behavior: 'smooth' });
            }
          } catch (e) {
             console.error('Error scrolling to anchor:', e);
          }
        } else {
          // This is just a "#" link, prevent default and do nothing else
          console.log('Empty anchor link clicked, preventing navigation');
        }
      }
    }
  }, false);
});
</script>
<style>
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
      transition: width 0.2s, height 0.2s;
    }
    
    ::-webkit-scrollbar:hover {
      width: 8px;
      height: 8px;
    }
    
    ::-webkit-scrollbar-track {
      background: transparent;
    }
    
    ::-webkit-scrollbar-thumb {
      background: linear-gradient(to bottom, 
        var(--primary, #7c3aed) 0%, 
        rgba(124, 58, 237, 0.7) 50%,
        var(--primary, #7c3aed) 100%);
      border-radius: 100vh;
      border: 1px solid transparent;
      background-clip: padding-box;
      box-shadow: 0 0 5px rgba(124, 58, 237, 0.3);
    }
    
    ::-webkit-scrollbar-thumb:hover {
      background: linear-gradient(to bottom, 
        rgb(137, 70, 248) 0%, 
        rgba(137, 70, 248, 0.8) 50%,
        rgb(137, 70, 248) 100%);
      border: 0px solid transparent;
      box-shadow: 0 0 8px rgba(124, 58, 237, 0.5);
    }
    
    ::-webkit-scrollbar-corner {
      background: transparent;
    }
    
    .scrolling::-webkit-scrollbar-thumb {
      animation: scrollGlow 1.5s ease-in-out infinite alternate;
    }
    
    @keyframes scrollGlow {
      from { box-shadow: 0 0 5px rgba(124, 58, 237, 0.3); }
      to { box-shadow: 0 0 10px rgba(124, 58, 237, 0.7); }
    }
  </style><style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.16 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0, 0, 0, 0);white-space:nowrap;border-width:0}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.-bottom-5{bottom:-1.25rem}.-right-5{right:-1.25rem}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.-mr-2{margin-right:-0.5rem}.mb-10{margin-bottom:2.5rem}.mb-12{margin-bottom:3rem}.mb-16{margin-bottom:4rem}.mb-2{margin-bottom:0.5rem}.mb-4{margin-bottom:1rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-10{margin-left:2.5rem}.ml-4{margin-left:1rem}.mr-2{margin-right:0.5rem}.mt-1{margin-top:0.25rem}.mt-4{margin-top:1rem}.mt-8{margin-top:2rem}.block{display:block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-10{height:2.5rem}.h-12{height:3rem}.h-14{height:3.5rem}.h-16{height:4rem}.h-5{height:1.25rem}.h-6{height:1.5rem}.h-8{height:2rem}.w-10{width:2.5rem}.w-12{width:3rem}.w-14{width:3.5rem}.w-5{width:1.25rem}.w-6{width:1.5rem}.w-8{width:2rem}.w-full{width:100%}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-4xl{max-width:56rem}.max-w-7xl{max-width:80rem}.max-w-md{max-width:28rem}.max-w-xs{max-width:20rem}.flex-shrink-0{flex-shrink:0}.transform{transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-start{align-items:flex-start}.items-center{align-items:center}.items-baseline{align-items:baseline}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-12{gap:3rem}.gap-2{gap:0.5rem}.gap-4{gap:1rem}.gap-8{gap:2rem}.space-x-4 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1rem * var(--tw-space-x-reverse));margin-left:calc(1rem * calc(1 - var(--tw-space-x-reverse)))}.space-x-6 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1.5rem * var(--tw-space-x-reverse));margin-left:calc(1.5rem * calc(1 - var(--tw-space-x-reverse)))}.space-y-1 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.25rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.25rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-md{border-radius:0.375rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-4{border-width:4px}.border-t{border-top-width:1px}.border-gray-700{--tw-border-opacity:1;border-color:rgb(55 65 81 / var(--tw-border-opacity, 1))}.border-gray-800{--tw-border-opacity:1;border-color:rgb(31 41 55 / var(--tw-border-opacity, 1))}.border-purple-500{--tw-border-opacity:1;border-color:rgb(168 85 247 / var(--tw-border-opacity, 1))}.border-transparent{border-color:transparent}.bg-black{--tw-bg-opacity:1;background-color:rgb(0 0 0 / var(--tw-bg-opacity, 1))}.bg-blue-500{--tw-bg-opacity:1;background-color:rgb(59 130 246 / var(--tw-bg-opacity, 1))}.bg-blue-600{--tw-bg-opacity:1;background-color:rgb(37 99 235 / var(--tw-bg-opacity, 1))}.bg-gray-700{--tw-bg-opacity:1;background-color:rgb(55 65 81 / var(--tw-bg-opacity, 1))}.bg-gray-800{--tw-bg-opacity:1;background-color:rgb(31 41 55 / var(--tw-bg-opacity, 1))}.bg-gray-800\/90{background-color:rgb(31 41 55 / 0.9)}.bg-gray-900{--tw-bg-opacity:1;background-color:rgb(17 24 39 / var(--tw-bg-opacity, 1))}.bg-gray-900\/30{background-color:rgb(17 24 39 / 0.3)}.bg-green-500{--tw-bg-opacity:1;background-color:rgb(34 197 94 / var(--tw-bg-opacity, 1))}.bg-indigo-600{--tw-bg-opacity:1;background-color:rgb(79 70 229 / var(--tw-bg-opacity, 1))}.bg-pink-600{--tw-bg-opacity:1;background-color:rgb(219 39 119 / var(--tw-bg-opacity, 1))}.bg-purple-500{--tw-bg-opacity:1;background-color:rgb(168 85 247 / var(--tw-bg-opacity, 1))}.bg-purple-600{--tw-bg-opacity:1;background-color:rgb(147 51 234 / var(--tw-bg-opacity, 1))}.bg-red-500{--tw-bg-opacity:1;background-color:rgb(239 68 68 / var(--tw-bg-opacity, 1))}.bg-red-600{--tw-bg-opacity:1;background-color:rgb(220 38 38 / var(--tw-bg-opacity, 1))}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.from-blue-400{--tw-gradient-from:#60a5fa var(--tw-gradient-from-position);--tw-gradient-to:rgb(96 165 250 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-gray-900{--tw-gradient-from:#111827 var(--tw-gradient-from-position);--tw-gradient-to:rgb(17 24 39 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-green-400{--tw-gradient-from:#4ade80 var(--tw-gradient-from-position);--tw-gradient-to:rgb(74 222 128 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-purple-400{--tw-gradient-from:#c084fc var(--tw-gradient-from-position);--tw-gradient-to:rgb(192 132 252 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-purple-900{--tw-gradient-from:#581c87 var(--tw-gradient-from-position);--tw-gradient-to:rgb(88 28 135 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-red-400{--tw-gradient-from:#f87171 var(--tw-gradient-from-position);--tw-gradient-to:rgb(248 113 113 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-pink-500{--tw-gradient-to:rgb(236 72 153 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #ec4899 var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-gray-800{--tw-gradient-to:#1f2937 var(--tw-gradient-to-position)}.to-indigo-800{--tw-gradient-to:#3730a3 var(--tw-gradient-to-position)}.to-orange-500{--tw-gradient-to:#f97316 var(--tw-gradient-to-position)}.to-pink-600{--tw-gradient-to:#db2777 var(--tw-gradient-to-position)}.to-purple-600{--tw-gradient-to:#9333ea var(--tw-gradient-to-position)}.to-red-500{--tw-gradient-to:#ef4444 var(--tw-gradient-to-position)}.to-teal-500{--tw-gradient-to:#14b8a6 var(--tw-gradient-to-position)}.p-2{padding:0.5rem}.p-3{padding:0.75rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-2{padding-left:0.5rem;padding-right:0.5rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-4{padding-left:1rem;padding-right:1rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.px-8{padding-left:2rem;padding-right:2rem}.py-12{padding-top:3rem;padding-bottom:3rem}.py-16{padding-top:4rem;padding-bottom:4rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.pb-12{padding-bottom:3rem}.pb-3{padding-bottom:0.75rem}.pt-2{padding-top:0.5rem}.pt-24{padding-top:6rem}.text-center{text-align:center}.font-sans{font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.font-bold{font-weight:700}.font-medium{font-weight:500}.font-semibold{font-weight:600}.leading-tight{line-height:1.25}.text-gray-100{--tw-text-opacity:1;color:rgb(243 244 246 / var(--tw-text-opacity, 1))}.text-gray-300{--tw-text-opacity:1;color:rgb(209 213 219 / var(--tw-text-opacity, 1))}.text-gray-400{--tw-text-opacity:1;color:rgb(156 163 175 / var(--tw-text-opacity, 1))}.text-gray-500{--tw-text-opacity:1;color:rgb(107 114 128 / var(--tw-text-opacity, 1))}.text-green-500{--tw-text-opacity:1;color:rgb(34 197 94 / var(--tw-text-opacity, 1))}.text-purple-200{--tw-text-opacity:1;color:rgb(233 213 255 / var(--tw-text-opacity, 1))}.text-red-500{--tw-text-opacity:1;color:rgb(239 68 68 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.placeholder-gray-400::placeholder{--tw-placeholder-opacity:1;color:rgb(156 163 175 / var(--tw-placeholder-opacity, 1))}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.backdrop-blur-sm{--tw-backdrop-blur:blur(4px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.hover\:scale-105:hover{--tw-scale-x:1.05;--tw-scale-y:1.05;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:bg-gray-600:hover{--tw-bg-opacity:1;background-color:rgb(75 85 99 / var(--tw-bg-opacity, 1))}.hover\:bg-gray-700:hover{--tw-bg-opacity:1;background-color:rgb(55 65 81 / var(--tw-bg-opacity, 1))}.hover\:bg-gray-900:hover{--tw-bg-opacity:1;background-color:rgb(17 24 39 / var(--tw-bg-opacity, 1))}.hover\:bg-indigo-700:hover{--tw-bg-opacity:1;background-color:rgb(67 56 202 / var(--tw-bg-opacity, 1))}.hover\:bg-purple-700:hover{--tw-bg-opacity:1;background-color:rgb(126 34 206 / var(--tw-bg-opacity, 1))}.hover\:bg-red-700:hover{--tw-bg-opacity:1;background-color:rgb(185 28 28 / var(--tw-bg-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.focus\:border-purple-500:focus{--tw-border-opacity:1;border-color:rgb(168 85 247 / var(--tw-border-opacity, 1))}.focus\:outline-none:focus{outline:2px solid transparent;outline-offset:2px}.focus\:ring-2:focus{--tw-ring-offset-shadow:var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);--tw-ring-shadow:var(--tw-ring-inset) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color);box-shadow:var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000)}.focus\:ring-purple-500:focus{--tw-ring-opacity:1;--tw-ring-color:rgb(168 85 247 / var(--tw-ring-opacity, 1))}.focus\:ring-offset-2:focus{--tw-ring-offset-width:2px}.focus\:ring-offset-gray-900:focus{--tw-ring-offset-color:#111827}@media (min-width: 640px){.sm\:flex-row{flex-direction:row}.sm\:px-3{padding-left:0.75rem;padding-right:0.75rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}}@media (min-width: 768px){.md\:mb-0{margin-bottom:0px}.md\:ml-6{margin-left:1.5rem}.md\:block{display:block}.md\:flex{display:flex}.md\:hidden{display:none}.md\:w-1\/2{width:50%}.md\:max-w-md{max-width:28rem}.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:items-center{align-items:center}.md\:justify-start{justify-content:flex-start}.md\:justify-between{justify-content:space-between}.md\:px-10{padding-left:2.5rem;padding-right:2.5rem}.md\:py-4{padding-top:1rem;padding-bottom:1rem}.md\:pb-20{padding-bottom:5rem}.md\:pt-32{padding-top:8rem}.md\:text-right{text-align:right}.md\:text-4xl{font-size:2.25rem;line-height:2.5rem}.md\:text-5xl{font-size:3rem;line-height:1}.md\:text-6xl{font-size:3.75rem;line-height:1}.md\:text-lg{font-size:1.125rem;line-height:1.75rem}}@media (min-width: 1024px){.lg\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.lg\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.lg\:px-8{padding-left:2rem;padding-right:2rem}}</style>
<script>
document.addEventListener('DOMContentLoaded', function() {
  document.body.addEventListener('click', function(event) {
    let anchor = event.target.closest('a');
    if (anchor) {
      const href = anchor.getAttribute('href');
      if (href && href.startsWith('#')) {
        event.preventDefault(); // Prevent default for all # links
        
        if (href.length > 1) {
          try {
            const targetId = decodeURIComponent(href.substring(1));
            const element = document.getElementById(targetId);
            if (element) {
              event.stopPropagation();
              element.scrollIntoView({ behavior: 'smooth' });
            }
          } catch (e) {
             console.error('Error scrolling to anchor:', e);
          }
        } else {
          // This is just a "#" link, prevent default and do nothing else
          console.log('Empty anchor link clicked, preventing navigation');
        }
      }
    }
  }, false);
});
</script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  document.body.addEventListener('click', function(event) {
    let anchor = event.target.closest('a');
    if (anchor) {
      const href = anchor.getAttribute('href');
      if (href && href.startsWith('#')) {
        event.preventDefault(); // Prevent default for all # links
        
        if (href.length > 1) {
          try {
            const targetId = decodeURIComponent(href.substring(1));
            const element = document.getElementById(targetId);
            if (element) {
              event.stopPropagation();
              element.scrollIntoView({ behavior: 'smooth' });
            }
          } catch (e) {
             console.error('Error scrolling to anchor:', e);
          }
        } else {
          // This is just a "#" link, prevent default and do nothing else
          console.log('Empty anchor link clicked, preventing navigation');
        }
      }
    }
  }, false);
});
</script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  document.body.addEventListener('click', function(event) {
    let anchor = event.target.closest('a');
    if (anchor) {
      const href = anchor.getAttribute('href');
      if (href && href.startsWith('#')) {
        event.preventDefault(); // Prevent default for all # links
        
        if (href.length > 1) {
          try {
            const targetId = decodeURIComponent(href.substring(1));
            const element = document.getElementById(targetId);
            if (element) {
              event.stopPropagation();
              element.scrollIntoView({ behavior: 'smooth' });
            }
          } catch (e) {
             console.error('Error scrolling to anchor:', e);
          }
        } else {
          // This is just a "#" link, prevent default and do nothing else
          console.log('Empty anchor link clicked, preventing navigation');
        }
      }
    }
  }, false);
});
</script>
<style>
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
      transition: width 0.2s, height 0.2s;
    }
    
    ::-webkit-scrollbar:hover {
      width: 8px;
      height: 8px;
    }
    
    ::-webkit-scrollbar-track {
      background: transparent;
    }
    
    ::-webkit-scrollbar-thumb {
      background: linear-gradient(to bottom, 
        var(--primary, #7c3aed) 0%, 
        rgba(124, 58, 237, 0.7) 50%,
        var(--primary, #7c3aed) 100%);
      border-radius: 100vh;
      border: 1px solid transparent;
      background-clip: padding-box;
      box-shadow: 0 0 5px rgba(124, 58, 237, 0.3);
    }
    
    ::-webkit-scrollbar-thumb:hover {
      background: linear-gradient(to bottom, 
        rgb(137, 70, 248) 0%, 
        rgba(137, 70, 248, 0.8) 50%,
        rgb(137, 70, 248) 100%);
      border: 0px solid transparent;
      box-shadow: 0 0 8px rgba(124, 58, 237, 0.5);
    }
    
    ::-webkit-scrollbar-corner {
      background: transparent;
    }
    
    .scrolling::-webkit-scrollbar-thumb {
      animation: scrollGlow 1.5s ease-in-out infinite alternate;
    }
    
    @keyframes scrollGlow {
      from { box-shadow: 0 0 5px rgba(124, 58, 237, 0.3); }
      to { box-shadow: 0 0 10px rgba(124, 58, 237, 0.7); }
    }
  </style><style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.16 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0, 0, 0, 0);white-space:nowrap;border-width:0}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.-bottom-5{bottom:-1.25rem}.-right-5{right:-1.25rem}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.-mr-2{margin-right:-0.5rem}.mb-10{margin-bottom:2.5rem}.mb-12{margin-bottom:3rem}.mb-16{margin-bottom:4rem}.mb-2{margin-bottom:0.5rem}.mb-4{margin-bottom:1rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-10{margin-left:2.5rem}.ml-4{margin-left:1rem}.mr-2{margin-right:0.5rem}.mt-1{margin-top:0.25rem}.mt-4{margin-top:1rem}.mt-8{margin-top:2rem}.block{display:block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-10{height:2.5rem}.h-12{height:3rem}.h-14{height:3.5rem}.h-16{height:4rem}.h-5{height:1.25rem}.h-6{height:1.5rem}.h-8{height:2rem}.w-10{width:2.5rem}.w-12{width:3rem}.w-14{width:3.5rem}.w-5{width:1.25rem}.w-6{width:1.5rem}.w-8{width:2rem}.w-full{width:100%}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-4xl{max-width:56rem}.max-w-7xl{max-width:80rem}.max-w-md{max-width:28rem}.max-w-xs{max-width:20rem}.flex-shrink-0{flex-shrink:0}.transform{transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-start{align-items:flex-start}.items-center{align-items:center}.items-baseline{align-items:baseline}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-12{gap:3rem}.gap-2{gap:0.5rem}.gap-4{gap:1rem}.gap-8{gap:2rem}.space-x-4 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1rem * var(--tw-space-x-reverse));margin-left:calc(1rem * calc(1 - var(--tw-space-x-reverse)))}.space-x-6 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1.5rem * var(--tw-space-x-reverse));margin-left:calc(1.5rem * calc(1 - var(--tw-space-x-reverse)))}.space-y-1 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.25rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.25rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-md{border-radius:0.375rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-4{border-width:4px}.border-t{border-top-width:1px}.border-gray-700{--tw-border-opacity:1;border-color:rgb(55 65 81 / var(--tw-border-opacity, 1))}.border-gray-800{--tw-border-opacity:1;border-color:rgb(31 41 55 / var(--tw-border-opacity, 1))}.border-purple-500{--tw-border-opacity:1;border-color:rgb(168 85 247 / var(--tw-border-opacity, 1))}.border-transparent{border-color:transparent}.bg-black{--tw-bg-opacity:1;background-color:rgb(0 0 0 / var(--tw-bg-opacity, 1))}.bg-blue-500{--tw-bg-opacity:1;background-color:rgb(59 130 246 / var(--tw-bg-opacity, 1))}.bg-blue-600{--tw-bg-opacity:1;background-color:rgb(37 99 235 / var(--tw-bg-opacity, 1))}.bg-gray-700{--tw-bg-opacity:1;background-color:rgb(55 65 81 / var(--tw-bg-opacity, 1))}.bg-gray-800{--tw-bg-opacity:1;background-color:rgb(31 41 55 / var(--tw-bg-opacity, 1))}.bg-gray-800\/90{background-color:rgb(31 41 55 / 0.9)}.bg-gray-900{--tw-bg-opacity:1;background-color:rgb(17 24 39 / var(--tw-bg-opacity, 1))}.bg-gray-900\/30{background-color:rgb(17 24 39 / 0.3)}.bg-green-500{--tw-bg-opacity:1;background-color:rgb(34 197 94 / var(--tw-bg-opacity, 1))}.bg-indigo-600{--tw-bg-opacity:1;background-color:rgb(79 70 229 / var(--tw-bg-opacity, 1))}.bg-pink-600{--tw-bg-opacity:1;background-color:rgb(219 39 119 / var(--tw-bg-opacity, 1))}.bg-purple-500{--tw-bg-opacity:1;background-color:rgb(168 85 247 / var(--tw-bg-opacity, 1))}.bg-purple-600{--tw-bg-opacity:1;background-color:rgb(147 51 234 / var(--tw-bg-opacity, 1))}.bg-red-500{--tw-bg-opacity:1;background-color:rgb(239 68 68 / var(--tw-bg-opacity, 1))}.bg-red-600{--tw-bg-opacity:1;background-color:rgb(220 38 38 / var(--tw-bg-opacity, 1))}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.from-blue-400{--tw-gradient-from:#60a5fa var(--tw-gradient-from-position);--tw-gradient-to:rgb(96 165 250 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-gray-900{--tw-gradient-from:#111827 var(--tw-gradient-from-position);--tw-gradient-to:rgb(17 24 39 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-green-400{--tw-gradient-from:#4ade80 var(--tw-gradient-from-position);--tw-gradient-to:rgb(74 222 128 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-purple-400{--tw-gradient-from:#c084fc var(--tw-gradient-from-position);--tw-gradient-to:rgb(192 132 252 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-purple-900{--tw-gradient-from:#581c87 var(--tw-gradient-from-position);--tw-gradient-to:rgb(88 28 135 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-red-400{--tw-gradient-from:#f87171 var(--tw-gradient-from-position);--tw-gradient-to:rgb(248 113 113 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-pink-500{--tw-gradient-to:rgb(236 72 153 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #ec4899 var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-gray-800{--tw-gradient-to:#1f2937 var(--tw-gradient-to-position)}.to-indigo-800{--tw-gradient-to:#3730a3 var(--tw-gradient-to-position)}.to-orange-500{--tw-gradient-to:#f97316 var(--tw-gradient-to-position)}.to-pink-600{--tw-gradient-to:#db2777 var(--tw-gradient-to-position)}.to-purple-600{--tw-gradient-to:#9333ea var(--tw-gradient-to-position)}.to-red-500{--tw-gradient-to:#ef4444 var(--tw-gradient-to-position)}.to-teal-500{--tw-gradient-to:#14b8a6 var(--tw-gradient-to-position)}.p-2{padding:0.5rem}.p-3{padding:0.75rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-2{padding-left:0.5rem;padding-right:0.5rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-4{padding-left:1rem;padding-right:1rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.px-8{padding-left:2rem;padding-right:2rem}.py-12{padding-top:3rem;padding-bottom:3rem}.py-16{padding-top:4rem;padding-bottom:4rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.pb-12{padding-bottom:3rem}.pb-3{padding-bottom:0.75rem}.pt-2{padding-top:0.5rem}.pt-24{padding-top:6rem}.text-center{text-align:center}.font-sans{font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.font-bold{font-weight:700}.font-medium{font-weight:500}.font-semibold{font-weight:600}.leading-tight{line-height:1.25}.text-gray-100{--tw-text-opacity:1;color:rgb(243 244 246 / var(--tw-text-opacity, 1))}.text-gray-300{--tw-text-opacity:1;color:rgb(209 213 219 / var(--tw-text-opacity, 1))}.text-gray-400{--tw-text-opacity:1;color:rgb(156 163 175 / var(--tw-text-opacity, 1))}.text-gray-500{--tw-text-opacity:1;color:rgb(107 114 128 / var(--tw-text-opacity, 1))}.text-green-500{--tw-text-opacity:1;color:rgb(34 197 94 / var(--tw-text-opacity, 1))}.text-purple-200{--tw-text-opacity:1;color:rgb(233 213 255 / var(--tw-text-opacity, 1))}.text-red-500{--tw-text-opacity:1;color:rgb(239 68 68 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.placeholder-gray-400::placeholder{--tw-placeholder-opacity:1;color:rgb(156 163 175 / var(--tw-placeholder-opacity, 1))}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.backdrop-blur-sm{--tw-backdrop-blur:blur(4px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.hover\:scale-105:hover{--tw-scale-x:1.05;--tw-scale-y:1.05;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:bg-gray-600:hover{--tw-bg-opacity:1;background-color:rgb(75 85 99 / var(--tw-bg-opacity, 1))}.hover\:bg-gray-700:hover{--tw-bg-opacity:1;background-color:rgb(55 65 81 / var(--tw-bg-opacity, 1))}.hover\:bg-gray-900:hover{--tw-bg-opacity:1;background-color:rgb(17 24 39 / var(--tw-bg-opacity, 1))}.hover\:bg-indigo-700:hover{--tw-bg-opacity:1;background-color:rgb(67 56 202 / var(--tw-bg-opacity, 1))}.hover\:bg-purple-700:hover{--tw-bg-opacity:1;background-color:rgb(126 34 206 / var(--tw-bg-opacity, 1))}.hover\:bg-red-700:hover{--tw-bg-opacity:1;background-color:rgb(185 28 28 / var(--tw-bg-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.focus\:border-purple-500:focus{--tw-border-opacity:1;border-color:rgb(168 85 247 / var(--tw-border-opacity, 1))}.focus\:outline-none:focus{outline:2px solid transparent;outline-offset:2px}.focus\:ring-2:focus{--tw-ring-offset-shadow:var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);--tw-ring-shadow:var(--tw-ring-inset) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color);box-shadow:var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000)}.focus\:ring-purple-500:focus{--tw-ring-opacity:1;--tw-ring-color:rgb(168 85 247 / var(--tw-ring-opacity, 1))}.focus\:ring-offset-2:focus{--tw-ring-offset-width:2px}.focus\:ring-offset-gray-900:focus{--tw-ring-offset-color:#111827}@media (min-width: 640px){.sm\:flex-row{flex-direction:row}.sm\:px-3{padding-left:0.75rem;padding-right:0.75rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}}@media (min-width: 768px){.md\:mb-0{margin-bottom:0px}.md\:ml-6{margin-left:1.5rem}.md\:block{display:block}.md\:flex{display:flex}.md\:hidden{display:none}.md\:w-1\/2{width:50%}.md\:max-w-md{max-width:28rem}.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:items-center{align-items:center}.md\:justify-start{justify-content:flex-start}.md\:justify-between{justify-content:space-between}.md\:px-10{padding-left:2.5rem;padding-right:2.5rem}.md\:py-4{padding-top:1rem;padding-bottom:1rem}.md\:pb-20{padding-bottom:5rem}.md\:pt-32{padding-top:8rem}.md\:text-right{text-align:right}.md\:text-4xl{font-size:2.25rem;line-height:2.5rem}.md\:text-5xl{font-size:3rem;line-height:1}.md\:text-6xl{font-size:3.75rem;line-height:1}.md\:text-lg{font-size:1.125rem;line-height:1.75rem}}@media (min-width: 1024px){.lg\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.lg\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.lg\:px-8{padding-left:2rem;padding-right:2rem}}</style></head>
<body class="bg-gray-900 text-gray-100 font-sans gjs-editing-mode">
    <!-- Navigation -->
    <nav class="fixed w-full bg-gray-800/90 backdrop-blur-md z-50 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 gjs-editable-section">
            <div class="flex items-center justify-between h-16 gjs-editable-section">
                <div class="flex items-center gjs-editable-section">
                    <div class="flex-shrink-0 gjs-editable-section">
                        <img src="https://firebasestorage.googleapis.com/v0/b/askmeanything-4cdef.firebasestorage.app/o/images%2FOOwKGpJvcGZJfYDlghjurGX30P23%2F1750804984547_photo_2025-06-25_05-17-50.jpg?alt=media&amp;token=1221b4fd-c398-4ec0-b30d-22d7204d184d" class="h-8 w-8 rounded-full gjs-editable-image" alt="Airdrop Hunter Logo" style="cursor: pointer;">
                    </div>
                    <div class="hidden md:block gjs-editable-section">
                        <div class="ml-10 flex items-baseline space-x-4 gjs-editable-section">
                            <a href="#home" class="px-3 py-2 rounded-md text-sm font-medium bg-purple-600 text-white gjs-editable-link">Home</a>
                            <a href="#services" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">Services</a>
                            <a href="#features" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">Features</a>
                            <a href="#about" class="px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">About</a>
                        </div>
                    </div>
                </div>
                <div class="hidden md:block gjs-editable-section">
                    <div class="ml-4 flex items-center md:ml-6 gjs-editable-section">
                        <a href="#contact" class="px-4 py-2 border border-transparent rounded-md text-sm font-medium text-white bg-indigo-600 hover:bg-indigo-700 gjs-editable-link">Join Now</a>
                    </div>
                </div>
                <div class="-mr-2 flex md:hidden gjs-editable-section">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none" aria-controls="mobile-menu" aria-expanded="false" id="mobile-menu-button" style="pointer-events: auto; cursor: pointer;">
                        <span class="sr-only">Open main menu</span>
                        <svg class="block h-6 w-6 gjs-editable-icon" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true" style="cursor: pointer;">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>

        <div class="md:hidden hidden gjs-editable-section" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 gjs-editable-section">
                <a href="#home" class="block px-3 py-2 rounded-md text-base font-medium text-white bg-gray-900 gjs-editable-link">Home</a>
                <a href="#services" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">Services</a>
                <a href="#features" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">Features</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white gjs-editable-link">About</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-white bg-indigo-600 hover:bg-indigo-700 gjs-editable-link">Join Now</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="section pt-24 pb-12 md:pt-32 md:pb-20 px-4 sm:px-6 lg:px-8 bg-gradient-to-br from-gray-900 to-gray-800 gjs-editable-section">
        <div class="max-w-7xl mx-auto gjs-editable-section">
            <div class="md:flex md:items-center md:justify-between gjs-editable-section">
                <div class="md:w-1/2 mb-10 md:mb-0 gjs-editable-section">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight gjs-editable-text" contenteditable="true" style="font-size: 70px !important;">
                        <span class="gradient-text bg-gradient-to-r from-purple-400 via-pink-500 to-red-500 animate__animated animate__fadeInUp gjs-editable-text gjs-inline-text" contenteditable="true">Airdrops Choice</span></h1>
                    <p class="text-xl text-gray-300 mb-8 gjs-editable-text" contenteditable="true">Your friendly neighborhood airdrop choice helping you find the best Web3 opportunities</p>
                    <div class="flex flex-wrap gap-4 gjs-editable-section">
                        <a href="#contact" class="px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 md:py-4 md:text-lg md:px-10 transition-all duration-300 transform hover:scale-105 gjs-editable-link">
                            Join Now
                        </a>
                        <a href="#services" class="px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-gray-700 hover:bg-gray-600 md:py-4 md:text-lg md:px-10 transition-all duration-300 transform hover:scale-105 gjs-editable-link">
                            Learn More
                        </a>
                    </div>
                    <div class="mt-8 flex space-x-6 gjs-editable-section">
                        <a href="https://x.com/airdropschoice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                            <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">Twitter</span>
                            <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                                <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                            </svg>
                        </a>
                        <a href="https://youtube.com/@airdropschoice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                            <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">YouTube</span>
                            <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                                <path fill-rule="evenodd" d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z" clip-rule="evenodd"></path>
                            </svg>
                        </a>
                        <a href="https://www.tiktok.com/@airdrops_choice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                            <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">TikTok</span>
                            <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                                <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"></path>
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center gjs-editable-section">
                    <div class="relative w-full max-w-md gjs-editable-section">
                        <img src="https://firebasestorage.googleapis.com/v0/b/askmeanything-4cdef.firebasestorage.app/o/images%2FOOwKGpJvcGZJfYDlghjurGX30P23%2F1750804984547_photo_2025-06-25_05-17-50.jpg?alt=media&amp;token=1221b4fd-c398-4ec0-b30d-22d7204d184d" class="rounded-full border-4 border-purple-500 shadow-xl floating w-full max-w-xs md:max-w-md animate__animated animate__fadeInUp gjs-editable-image" alt="Airdrop Hunter" style="cursor: pointer;">
                        <div class="absolute -bottom-5 -right-5 bg-purple-600 rounded-full p-3 shadow-lg pulse gjs-editable-section">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                            </svg>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section py-16 px-4 sm:px-6 lg:px-8 bg-gray-800 gjs-editable-section">
        <div class="max-w-7xl mx-auto gjs-editable-section">
            <div class="text-center mb-16 gjs-editable-section">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text bg-gradient-to-r from-purple-400 to-pink-600 gjs-editable-text animate__animated animate__fadeInUp" contenteditable="true">What I Do</h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto gjs-editable-text" contenteditable="true">Your guide to finding the most profitable Web3 airdrop opportunities</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 gjs-editable-section">
                <div class="bg-gray-700 rounded-xl p-6 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="w-14 h-14 bg-purple-600 rounded-full flex items-center justify-center mb-4 gjs-editable-section">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Research Early-stage Web3 Projects</h3>
                    <p class="text-gray-300 gjs-editable-text" contenteditable="true">I dig deep to uncover promising new projects before they hit mainstream.</p>
                </div>
                <div class="bg-gray-700 rounded-xl p-6 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="w-14 h-14 bg-indigo-600 rounded-full flex items-center justify-center mb-4 gjs-editable-section">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Analyze Tokenomics &amp; Utility</h3>
                    <p class="text-gray-300 gjs-editable-text" contenteditable="true">Detailed analysis of token economics to identify sustainable projects.</p>
                </div>
                <div class="bg-gray-700 rounded-xl p-6 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="w-14 h-14 bg-pink-600 rounded-full flex items-center justify-center mb-4 gjs-editable-section">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Share Profitable Airdrop Opportunities</h3>
                    <p class="text-gray-300 gjs-editable-text" contenteditable="true">Curated list of the most promising airdrops with step-by-step guides.</p>
                </div>
                <div class="bg-gray-700 rounded-xl p-6 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="w-14 h-14 bg-blue-600 rounded-full flex items-center justify-center mb-4 gjs-editable-section">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Track Emerging Trends</h3>
                    <p class="text-gray-300 gjs-editable-text" contenteditable="true">Stay ahead of the curve with insights into the latest Web3 narratives.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="section py-16 px-4 sm:px-6 lg:px-8 bg-gray-900 gjs-editable-section">
        <div class="max-w-7xl mx-auto gjs-editable-section">
            <div class="text-center mb-16 gjs-editable-section">
                <h2 class="text-3xl md:text-5xl font-bold mb-4 gradient-text bg-gradient-to-r from-blue-400 to-purple-600 gjs-editable-text animate__animated animate__fadeInUp" contenteditable="true">Following Me Gets You</h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto gjs-editable-text" contenteditable="true">Early access to valuable Web3 resources and opportunities</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 gjs-editable-section">
                <div class="bg-gray-800 rounded-xl p-8 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="flex items-start mb-6 gjs-editable-section">
                        <div class="flex-shrink-0 gjs-editable-section">
                            <div class="w-12 h-12 bg-blue-500 rounded-full flex items-center justify-center gjs-editable-section">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="ml-4 gjs-editable-section">
                            <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Project Deep Dives</h3>
                            <p class="text-gray-300 gjs-editable-text" contenteditable="true">Comprehensive analysis of Web3 projects including team, technology, roadmap and potential.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-gray-800 rounded-xl p-8 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="flex items-start mb-6 gjs-editable-section">
                        <div class="flex-shrink-0 gjs-editable-section">
                            <div class="w-12 h-12 bg-green-500 rounded-full flex items-center justify-center gjs-editable-section">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="ml-4 gjs-editable-section">
                            <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Airdrop Tutorials</h3>
                            <p class="text-gray-300 gjs-editable-text" contenteditable="true">Step-by-step guides on how to qualify for and claim the most lucrative airdrops.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-gray-800 rounded-xl p-8 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="flex items-start mb-6 gjs-editable-section">
                        <div class="flex-shrink-0 gjs-editable-section">
                            <div class="w-12 h-12 bg-purple-500 rounded-full flex items-center justify-center gjs-editable-section">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="ml-4 gjs-editable-section">
                            <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Market Analysis</h3>
                            <p class="text-gray-300 gjs-editable-text" contenteditable="true">Regular updates on market trends, sentiment shifts, and emerging opportunities.</p>
                        </div>
                    </div>
                </div>
                <div class="bg-gray-800 rounded-xl p-8 shadow-lg card-hover gjs-editable-section animate__animated animate__fadeInUp">
                    <div class="flex items-start mb-6 gjs-editable-section">
                        <div class="flex-shrink-0 gjs-editable-section">
                            <div class="w-12 h-12 bg-red-500 rounded-full flex items-center justify-center gjs-editable-section">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-white gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="ml-4 gjs-editable-section">
                            <h3 class="text-xl font-semibold mb-2 gjs-editable-text" contenteditable="true">Breaking News &amp; Alpha</h3>
                            <p class="text-gray-300 gjs-editable-text" contenteditable="true">Timely alerts on important developments, partnerships, and insider information.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem/Solution Section -->
    <section id="about" class="section py-16 px-4 sm:px-6 lg:px-8 bg-gray-800 gjs-editable-section">
        <div class="max-w-7xl mx-auto gjs-editable-section">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center gjs-editable-section">
                <div class="gjs-editable-section">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 gradient-text bg-gradient-to-r from-red-400 to-orange-500 gjs-editable-text animate__animated animate__fadeInUp" contenteditable="true">The Problem</h2>
                    <p class="text-lg text-gray-300 mb-6 gjs-editable-text" contenteditable="true">Finding the right airdrops among thousands of Web3 projects is challenging and time-consuming.</p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-red-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Overwhelming number of projects offering airdrops</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-red-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Difficulty distinguishing legitimate projects from scams</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-red-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Risk of wasting time and resources on worthless airdrops</span>
                        </li>
                    </ul>
                </div>
                <div class="gjs-editable-section">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 gradient-text bg-gradient-to-r from-green-400 to-teal-500 gjs-editable-text animate__animated animate__fadeInUp" contenteditable="true">The Solution</h2>
                    <p class="text-lg text-gray-300 mb-6 gjs-editable-text" contenteditable="true">Airdrop Hunter provides curated, high-quality airdrop opportunities with thorough vetting.</p>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-green-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">In-depth research on early-stage Web3 projects</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-green-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Comprehensive tokenomics and utility analysis</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-green-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Regular updates on profitable airdrop opportunities</span>
                        </li>
                        <li class="flex items-start">
                            <svg class="h-6 w-6 text-green-500 mr-2 mt-1 gjs-editable-icon" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="cursor: pointer;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                            </svg>
                            <span class="text-gray-300 gjs-editable-text gjs-inline-text" contenteditable="true">Tracking of emerging trends and narratives</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section id="contact" class="section py-16 px-4 sm:px-6 lg:px-8 bg-gradient-to-br from-purple-900 to-indigo-800 gjs-editable-section">
        <div class="max-w-4xl mx-auto text-center gjs-editable-section">
            <h2 class="text-3xl md:text-5xl font-bold mb-6 text-white gjs-editable-text" contenteditable="true">Join the Airdrop Choice Community</h2>
            <p class="text-xl text-purple-200 mb-10 max-w-2xl mx-auto gjs-editable-text" contenteditable="true">Get early access to the best Web3 airdrop opportunities and maximize your crypto earnings.</p>
            
            <div class="flex flex-col sm:flex-row justify-center gap-4 mb-12 gjs-editable-section">
                <a href="https://x.com/airdropschoice" target="_blank" rel="noopener" class="px-6 py-3 bg-black text-white rounded-lg font-medium flex items-center justify-center gap-2 hover:bg-gray-900 transition-colors gjs-editable-link">
                    <svg class="h-5 w-5 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                        <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                    </svg>
                    Follow on Twitter
                </a>
                <a href="https://youtube.com/@airdropschoice" target="_blank" rel="noopener" class="px-6 py-3 bg-red-600 text-white rounded-lg font-medium flex items-center justify-center gap-2 hover:bg-red-700 transition-colors gjs-editable-link">
                    <svg class="h-5 w-5 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                        <path fill-rule="evenodd" d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z" clip-rule="evenodd"></path>
                    </svg>
                    Subscribe on YouTube
                </a>
                <a href="https://www.tiktok.com/@airdrops_choice" target="_blank" rel="noopener" class="px-6 py-3 bg-gray-800 text-white rounded-lg font-medium flex items-center justify-center gap-2 hover:bg-gray-700 transition-colors gjs-editable-link">
                    <svg class="h-5 w-5 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                        <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"></path>
                    </svg>
                    Follow on TikTok
                </a>
            </div>

            <div class="bg-gray-900/30 backdrop-blur-sm rounded-xl p-8 max-w-2xl mx-auto gjs-editable-section">
                <h3 class="text-2xl font-bold mb-6 text-white gjs-editable-text" contenteditable="true">Stay Updated</h3>
                <form class="space-y-4" id="subscribe-form">
                    <div class="gjs-editable-section">
                        <input type="email" id="email" name="email" required="" class="w-full px-4 py-3 rounded-lg bg-gray-800 border border-gray-700 focus:border-purple-500 focus:outline-none text-white placeholder-gray-400" placeholder="Your email address">
                    </div>
                    <button type="submit" class="w-full px-6 py-3 bg-purple-600 text-white font-medium rounded-lg hover:bg-purple-700 transition-colors focus:outline-none focus:ring-2 focus:ring-purple-500 focus:ring-offset-2 focus:ring-offset-gray-900" style="pointer-events: auto; cursor: pointer;">
                        Get Airdrop Alerts
                    </button>
                </form>
                <p class="text-sm text-purple-200 mt-4 gjs-editable-text" contenteditable="true">We respect your privacy. Unsubscribe at any time.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 py-12 px-4 sm:px-6 lg:px-8 border-t border-gray-800 gjs-editable-section">
        <div class="max-w-7xl mx-auto gjs-editable-section">
            <div class="md:flex md:items-center md:justify-between gjs-editable-section">
                <div class="flex justify-center md:justify-start space-x-6 mb-8 md:mb-0 gjs-editable-section">
                    <a href="https://x.com/airdropschoice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                        <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">Twitter</span>
                        <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                            <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                        </svg>
                    </a>
                    <a href="https://youtube.com/@airdropschoice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                        <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">YouTube</span>
                        <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                            <path fill-rule="evenodd" d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z" clip-rule="evenodd"></path>
                        </svg>
                    </a>
                    <a href="https://www.tiktok.com/@airdrops_choice" target="_blank" rel="noopener" class="social-icon text-gray-400 hover:text-white gjs-editable-link">
                        <span class="sr-only gjs-editable-text gjs-inline-text" contenteditable="true">TikTok</span>
                        <svg class="h-6 w-6 gjs-editable-icon" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" style="cursor: pointer;">
                            <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"></path>
                        </svg>
                    </a>
                </div>
                <div class="text-center md:text-right gjs-editable-section">
                    <p class="text-base text-gray-400 gjs-editable-text" contenteditable="true">© 2024 Airdrop Hunter. All rights reserved.</p>
                    <p class="text-sm text-gray-500 mt-1 gjs-editable-text" contenteditable="true">Created with love by <a href="https://linos.ai" target="_blank" rel="noopener" class="text-gray-400 hover:text-white gjs-editable-link">Linos.ai</a></p>
                </div>
            </div>
        </div>
    </footer>

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
            alert(`Thank you for subscribing with ${email}! You'll receive airdrop alerts soon.`);
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
