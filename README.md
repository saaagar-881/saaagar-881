
   <br />
    <br />


  <h3 align="center">A simple HTML link tree created with TailwindCSS.</h3>

  <p align="center">
    It is super easy to use this link tree.
    <br />
    <br />
    <a href="https://upbeat-dubinsky-abcc9c.netlify.app/">View Demo</a>
    ·
    <a href="https://tailwindcss.com/">TailwindCSS</a>
  </p>
</p>

<img src="https://www.hub.flaced.de/index.php/apps/files_sharing/publicpreview/5ESjLokRdE3T32y?x=1920&y=587&a=true&file=linktree.png&scalingup=0">


## Built With

💻 [HTML](https://wiki.selfhtml.org/wiki/HTML)<br>
🖼🎨 [TailwindCSS](https://tailwindcss.com/)


## Getting Started

There are two different ways to use this link tree:<br>
You can download this code and host it on your own host. You can also easily add this LinkTree to your Netlify account with one click.


[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/flaced/simple-html-linktree)


## Customize

If you want to add another link you can do it with the following code. You have to add it in the code below the comments.

```html
<!-- LINK -->
<div class="px-4 mx-auto mb-4 sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
  <div class="grid max-w-screen-lg sm:mx-auto">
    <a href="#" target="_blank" aria-label="View item" title="View item" class="relative block p-px overflow-hidden transition duration-300 transform border rounded shadow-sm hover:scale-105 group hover:shadow-xl">
      <div class="absolute bottom-0 left-0 w-full h-1 duration-300 origin-left transform scale-x-0 bg-gray-800 group-hover:scale-x-100"></div>
      <div class="absolute bottom-0 left-0 w-1 h-full duration-300 origin-bottom transform scale-y-0 bg-gray-800 group-hover:scale-y-100"></div>
      <div class="absolute top-0 left-0 w-full h-1 duration-300 origin-right transform scale-x-0 bg-gray-800 group-hover:scale-x-100"></div>
      <div class="absolute bottom-0 right-0 w-1 h-full duration-300 origin-top transform scale-y-0 bg-gray-800 group-hover:scale-y-100"></div>
      <div class="relative flex items-center justify-between p-5 bg-white rounded-sm">
        <div class="pr-4">
            <h6 class="mb-2 font-semibold leading-5">Lorem Ipsum</h6>
            <p class="text-sm text-gray-900">Lorem ipsum dolor sit amet, consetetur sadipscing elitr</p>
        </div>
        <div class="flex items-center justify-center">
          <svg class="w-3 text-gray-700 transition-colors duration-200 group-hover:text-deep-purple-accent-400" fill="currentColor" viewBox="0 0 12 12">
            <path d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"></path>
          </svg>
        </div>
      </div>
    </a>
  </div>
</div>
<!-- LINK -->
```

If you want to create a new category you can copy the following code. You have to paste this code under the comment lines again.

```html
<!-- DIVIDER -->
<div class="mt-7 px-4 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
<div class="grid max-w-screen-lg sm:mx-auto">
<div class="flex flex-row mb-4 items-center justify-center">
     <hr class="w-full border-gray-300">
        <label class="mx-2 text-sm text-center text-gray-600 font-medium uppercase">LoremIpsum</label>
     <hr class="w-full border-gray-300">
</div>
</div>
</div>
<!-- DIVIDER -->
```

If you want a link without description you can copy the following code.

```html
    <!-- LINK -->
    <div class="px-4 mx-auto mb-4 sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
      <div class="grid max-w-screen-lg sm:mx-auto">
        <a href="https://covid-flaced.netlify.app/" target="_blank" aria-label="View item" title="View item" class="relative block p-px overflow-hidden transition duration-300 transform border rounded shadow-sm hover:scale-105 group hover:shadow-xl">
          <div class="absolute bottom-0 left-0 w-full h-1 duration-300 origin-left transform scale-x-0 bg-gray-800 group-hover:scale-x-100"></div>
          <div class="absolute bottom-0 left-0 w-1 h-full duration-300 origin-bottom transform scale-y-0 bg-gray-800 group-hover:scale-y-100"></div>
          <div class="absolute top-0 left-0 w-full h-1 duration-300 origin-right transform scale-x-0 bg-gray-800 group-hover:scale-x-100"></div>
          <div class="absolute bottom-0 right-0 w-1 h-full duration-300 origin-top transform scale-y-0 bg-gray-800 group-hover:scale-y-100"></div>
          <div class="relative flex items-center justify-between p-5 bg-white rounded-sm">
            <div class="pr-4">
                <h6 class="font-semibold leading-5">LoremIpsum</h6>
            </div>
            <div class="flex items-center justify-center">
              <svg class="w-3 text-gray-700 transition-colors duration-200 group-hover:text-deep-purple-accent-400" fill="currentColor" viewBox="0 0 12 12">
                <path d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"></path>
              </svg>
            </div>
          </div>
        </a>
      </div>
    </div>
    <!-- LINK -->
```

