<template>
<div class="bg-gray-200">
  <div class="container mx-auto px-6 py-12">
    <!-- <full-calendar class="" :events="fcEvents" locale="en"></full-calendar> -->
    <h1 class="text-blue-500 font-bold text-xl text-center">Our Events</h1>
    <div class="flex items-center justify-center">
      <div class="grid gap-6 grid-cols-1 sm:grid-cols-2 lg:gap-12 lg:grid-cols-3 mt-10">
        <div class="w-full mt-8 md:mt-0 md:max-w-xs">
          <div class="bg-white shadow-lg rounded-lg overflow-hidden">
            <div class="h-56 bg-cover object-center" style=" background-image: url('https://images.unsplash.com/photo-1523580494863-6f3031224c94?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80')"></div>
            <div class="flex py-4 px-6">
              <div class="flex flex-col items-center justify-center">
                <div class="text-blue-600 uppercase">Jun</div>
                <div class="font-bold text-gray-800">11</div>
              </div>
              <div class="ml-4">
                <h2 class="text-gray-800 text-xl font-bold">Lorem accumsan et.</h2>
                <p class="text-gray-600 text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique, ipsam deleniti</p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full mt-8 md:mt-0 md:max-w-xs">
          <div class="bg-white shadow-lg rounded-lg overflow-hidden">
            <div class="h-56 bg-cover object-center" style=" background-image: url('https://images.unsplash.com/photo-1523580494863-6f3031224c94?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80')"></div>
            <div class="flex py-4 px-6">
              <div class="flex flex-col items-center justify-center">
                <div class="text-blue-600 uppercase">May</div>
                <div class="font-bold text-gray-800">23</div>
              </div>
              <div class="ml-4">
                <h2 class="text-gray-800 text-xl font-bold">Lorem accumsan et.</h2>
                <p class="text-gray-600 text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique, ipsam deleniti</p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full mt-8 md:mt-0 md:max-w-xs">
          <div class="bg-white shadow-lg rounded-lg overflow-hidden">
            <div class="h-56 bg-cover object-center" style=" background-image: url('https://images.unsplash.com/photo-1523580494863-6f3031224c94?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80')"></div>
            <div class="flex py-4 px-6">
              <div class="flex flex-col items-center justify-center">
                <div class="text-blue-600 uppercase">Aug</div>
                <div class="font-bold text-gray-800">2</div>
              </div>
              <div class="ml-4">
                <h2 class="text-gray-800 text-xl font-bold">Lorem accumsan et.</h2>
                <p class="text-gray-600 text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique, ipsam deleniti</p>
              </div>
            </div>
          </div>
        </div> 
      </div>
    </div>
    <div class="flex items-center justify-center mt-8">
      <a href="#" class="flex items-center justify-center w-full text-blue-500 text-center hover:underline">
        <span>All Events</span> 
        <svg class="h-6 w-6 fill-current ml-2" viewBox='0 0 512 512'>
          <path d='M64,256c0,106,86,192,192,192s192-86,192-192S362,64,256,64,64,150,64,256Z'/><polyline points='216 352 312 256 216 160'/>
        </svg>
      </a>
    </div>
  </div>
</div>
</template>

<script>
var demoEvents = [
	{
      title : 'Sunny Out of Office',
      start : '2020-04-01',
      end : '2020-04-06',
      YOUR_DATA : ['helllo'],
      cssClass  : ['career']
    }
]
export default {
 
    data () {
	return {
    /* eslint-disable no-mixed-spaces-and-tabs */
    fcEvents : demoEvents
    /* eslint-disable no-mixed-spaces-and-tabs */
	}
  },
  // components : {
	// 'full-calendar': require('vue-fullcalendar')	
  // },
  name: 'Events',
  props: {
    msg: String
  }
}
</script>
