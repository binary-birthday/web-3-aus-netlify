<script>
  import { fade, draw } from 'svelte/transition';
  import { onMount } from 'svelte';
  
  let visible = false;
  
  onMount(() => {
    visible = true;
  })

</script>
  
<style>
  svg {
    z-index: -5;
  }

  .grid {
    display: grid;
    grid-template-columns: 1fr 95%;
  }

</style>

<main transition:fade class="w-100">
  {#if visible}
    <svg class="absolute o-50 w-100 h5 h-50-m h-75-l" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 1920 1080" preserveAspectRatio="xMidYMid meet">
      <defs>
        <clipPath id="a">
          <path d="M0 0h1920v1080H0z"/>
        </clipPath>
        <clipPath id="b">
          <path d="M0 0h1920v1080H0z"/>
        </clipPath>
      </defs>
      <g clip-path="url(#a)">
        <g clip-path="url(#b)" display="block" >
          <g display="block">
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1195.26293945 218.46099854l57.26599884     278.16699218-57.26599884 278.16699219"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1195.26293945 218.46099854l41.62599945     279.18299222-41.62599945 277.15099215"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1195.26293945 218.46099854l25.98600006     280.19899225-25.98600006 276.13499212"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1195.26293945 218.46099854l10.34599972     281.21499228-10.34599972 275.11899209"/>
          </g>
          <g display="block">
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.71299744 852.57098389l-79.44999695-226.38799286    79.07499695-324.69599152"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.71300125 852.57098389L658.9109993    616.40699005l65.55200195-315.23200226"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.71300125 852.57098389l-52.15200043-245.939991    51.96430016-305.51899338"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.71300316 852.57098389l-38.50400162-255.71699143    38.25400162-295.61699295"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.94700432 852.70199585l-24.8543001-265.491992     24.2290001-285.71699238"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M724.71300077 852.57098389L713.50700045     577.3019917l10.70600032-275.56499219"/>
          </g>
          <g display="block">
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M888.685997     551.78199387c-40.413002-29.35100174-75.8880081-55.11500168-75.8880081-55.11500168l191.50300597-139.08399964L1195.80430085     218.5v556.33398438l-191.50300598-139.08399964s-62.13199997-45.12499237-115.61499786-83.96799087"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M912.33499908 400.83200073c28.6739998-11.9449997    82.09999848-34.20199585 82.09999848-34.20199585l180.03999328-116.50100708 11.4630127 255.58400294-9.47801208    255.07299474-182.0249939-115.98999023-99.8043003-41.57700348-91.69800568-97.50600103 91.69800567-97.50430056s7.1870041-2.99399566    17.70500183-7.37599945"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M900.52199554 390.02400208c32.94099808-5.62399292     84.04699762-14.34899903 84.04699762-14.34899903l168.57799476-93.91700744 22.92401123 233.00000757-22.75500489     231.27899938-168.7470011-92.19499206-111.26699884-18.99501038-80.23600006-120.08899694 80.23600006-120.08699793s11.55599976-1.97299957    27.22000122-4.64700317"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M891.50299835 382.29430037c35.87499619 1.04800415     83.1979975 2.43099975 83.1979975 2.43099975l157.1160055-71.33399963 34.3869934 210.41699927-34.3869934    210.42000634-157.1160055-71.33601379-122.72900336 3.5880127-68.77300262-142.67200525 68.77300262-142.66899817s17.63300324.51499939 39.53100586    1.15499878"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M884.16400146 378.03599548c37.39899827 7.29299927     80.67099708 15.73199463 80.67099708 15.73199463l145.6529928-48.75300598 45.8430061 187.83600562-45.8430061    187.83800561-145.6529928-48.75401306-134.19100135 26.17100525-57.31100464-165.2549978 57.31100464-165.25200599s25.05899811 4.88700867   53.52000427  10.43701172"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M877.0289917 376.72698975c38.03500366 12.7310028    77.94300244 26.08799743 77.94300244 26.08799743l134.19099426-26.16900635 57.31201172 165.25200599-57.31201172   165.2549978-134.19099426-26.17100525-145.65400696 48.75401306-45.84899902-187.83800561 45.84899902-187.83600562s33.08200836 11.07299805    67.71400452 22.66500855"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M869.3160019 377.4520111c38.33300399 17.40499879    75.7860031 34.44300367 75.7860031 34.44300367l122.72899628-3.58700561 68.77300263 142.66999816-68.77300263    142.67199707-122.72899628-3.58799743-157.11599731 71.33599853-34.38600159-210.41999817 34.38600159-210.41900634s41.14899445 18.68301391  81.3299942  36.92601013"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M860.6210022 379.33799744c38.68499756 21.55200195     74.61499841 41.56900024 74.61499841 41.56900024l111.26699774 18.9960022 80.23500824 120.08799743-80.23500824 120.08799744-111.26699774    18.9960022-168.57799585 93.91799927-22.92500305-233.0019989 22.92500305-233.0019989s48.85399628 27.21800231 93.96299744 52.34899902"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M850.73999786 381.66299438c39.33499909 25.45199585    74.62899726 48.2899933 74.62899726 48.2899933l99.80430085 41.57800292 91.69799805 97.5049967-91.69799805 97.5069967-99.80430085   41.57699586-180.04100745 116.50201416-11.46099853-255.58600672 11.46099853-255.58299963s55.90700531 36.17599487 105.4120102 68.24300671"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1031.1190033 522.96901321c40.41200256 29.35100174    75.88700866 55.11500168 75.88700866 55.11500168L915.50300598 717.16700745 724 856.25100708V578.08401489 299.91702271l191.50300598   139.08299255s62.13199997 45.125 115.61599732 83.96899795M1130.86299706     817.42898178c-3.67100144-6.06900024-6.21500206-10.27430017-6.21500206-10.27430017h65.63400268l-32.81700134    54.25400162s-17.08799935-28.24300083-26.60199928-43.98000145"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1128.74299622    809.6359849c-2.49399949-1.51430016-4.09500122-2.48430043-4.09500122-2.48430043m65.63400268 0l-32.81600134   19.88430078s-19.92199953-12.07430034-28.72300012-17.40300035"/>
            <path in:draw="{{duration: 4300}}" fill="none" stroke="#070506" stroke-miterlimit="10" d="M1128.74299622    812.15501213c-2.49399949-3.04599953-4.09500122-5-4.09500122-5m65.63400268 0l-32.81600134    40.06399918s-19.92199953-24.32099963-28.72300012-35.06399918"/>
          </g>
        </g>
      </g>
    </svg>
  {/if}
  
<div class="flex flex-column w-100 h-100">
  <div class="grid h-50 mt2 h-75-l  ml2-ns ml4-m ml6-l mb3 mb4-m mb5-l">
    <div></div>
    <div class="flex f3 f2-m f1-l flex-column justify-center content-center">
     <h1 class="black-90"> WEB 3 <br> AUSTRALIA </h1>
    </div>
  </div>
  <div class="w-100 flex flex-column justify-center items-center">
    <article class="flex w-100 mb3 mb4-m mb5 flex-column justify-center items-center" >
      <div class="flex w-100 w-70-l items-center justify center">
        <p class="f4 f2-m f2-l w-100 tc">Web3 Australia’s Goals</p>
      </div>
      <div class="flex flex-column w-90 w-80-l items-center justify-center f5 f3-m f3-l tc">
        <p>Advance the development and safe implementation of Web3 and decentralised technologies.</p>
	      <p>Provide community education on technologies that preserve data rights and data security.</p>
	      <p>Promote the prevention of consumer data misuse, including mass surveillance and invasion of privacy by global technology companies and governments.</p>
      </div>
	    
    </article>
  </div>
</div>
</main>
