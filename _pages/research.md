---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<style>
.sidenav {
  width: 300px;
  position: fixed;
  z-index: 1;
  top: 200px;
  right: 10px;
  background: #fff;
  overflow-x: hidden;
  padding: 8px 0;
}

.sidenav a {
  padding: 1px 1px 6px 1px;
  text-decoration: none;
  font-size: 14px;
  color: #2196F3;
  display: block;
}

.sidenav a:hover {
  color: #064579;
}

.main {
  margin-left: 165px; /* Same width as the sidebar + left position in px */
  font-size: 15px; /* Increased text to enable scrolling */
  padding: 0px 0px;
}

@media screen and (max-height: 500px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}

html {
    scroll-behavior: smooth !important;
}

:target::before {
  content: "";
  display: block;
  height: 80px; /* fixed header height*/
  margin: -80px 0 0; /* negative fixed header height */
}
</style>

<!-- side head -->
<div class="sidenav">
	<div id="navbar-collapse-03" class="collapse navbar-collapse">
		<ul style="font-family:verdana" style="list-style-type:none">
			<li><a href="#ResearchCTHM">Crogenic THM model</a></li>
			<li><a href="#ResearchFC">Frost cracking</a></li>
      <li><a href="#ResearchSlope">Rock slope stability analysis</a></li>
      <li><a href="#ResearchFlow">Flow transport in fractured porous media</a></li>
      <li><a href="#ResearchTC">Thermal cracking</a></li>
      <li><a href="#ResearchGrout">Grout migration</a></li>
      <li><a href="#ResearchHF">Hydraulic fracturing</a></li>
		</ul>
	</div>
</div>


<!-- content -->


<!-- Two-phase flow -->

<!-- frost induced Rockfall -->

<!-- 3D frost heave -->


<!-- CTHM coupling model -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchCTHM">Crogenic Thermal-Hydraulic-Mechanical Model</h2>
    <img src="/images/research/1CTHM.png" alt="" width="700"/><br>
    <img src="/images/research/1T.gif" alt="" width="250"/>    
    <img src="/images/research/1U.gif" alt="" width="250"/>  
    </center>
    <p> 
    We developed a coupled modeling approach to simulate cryogenic thermo-hydro-mechanical (THM) processes associated with a freezing medium, which is then implemented in the combined finite-discrete element method code (FDEM) for multi-physics simulation. The cryogenic THM model can well predict the evolution of strongly coupled processes observed in frozen media (e.g., heat transfer, water migration, and frost heave deformation), while also capturing, as emergent properties of the model, important phenomena (e.g., latent heat, cryogenic suction, ice expansion and distinct three-zone distribution) caused by water/ice phase change at laboratory and field scales, which are hardly to be all revealed by existing THM models.</p>
  </div>
</div>
<hr>


<!-- Frost cracking -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchFC">Frost cracking simulation</h2>
    <img src="/images/research/2background.png" alt="" width="600"/><br>
    Experimental and numerical tests<br>
    <img src="/images/research/21.png" alt="" width="300"/>
    <img src="/images/research/22.png" alt="" width="300"/>
    <img src="/images/research/23.png" alt="" width="300"/>
    <img src="/images/research/24.png" alt="" width="300"/>
    </center>
    <p> 
    Frost crack evolution induced by cyclic freeze-thaw is responsible for rock  deteriorationin cold regions and poses major threats to the stability and safety of infrastructure in rock. We present experimental and numerical works aimed at investigating the frost crack evolution in fissured rock masses, as well as the interaction between frost cracks. Results show that frost cracks initiate at the pre-existing fissure tips and propagate under the freeze-thaw treatment. Moreover, the frost crack evolution is significantly influenced by external stress conditions and frost crack interactions, forming several typical propagation patterns (e.g., deflection, coplanar and butterfly shape, etc.). 
    <a href="https://link.springer.com/article/10.1007/s00603-022-03111-3" target="_blank">Read more</a>.</p>
  </div>
</div>
<hr>


<!-- Slope stability -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchSlope">Rock slope stability analysis</h2> </center>
    <h3>Entire progressive failure process of rock slopes</h3>
      <center>
      <img src="/images/research/slope1.gif" alt="" width="180"/>
      <img src="/images/research/slope3.gif" alt="" width="250"/>
      <img src="/images/research/slope2.gif" alt="" width="270"/><br>
      </center>
      <p> We presented a novel approach (Y-slope) to simulate entire slope failure processes, from initiation, transport to deposition.
      <a href="https://www.sciencedirect.com/science/article/pii/S0266352X2100536X" target="_blank">Read more</a>.</p>   
    <h3>Influence of discontinuities</h3>
      <center>
      <img src="/images/research/slope6.gif" alt="" width="180"/>
      <img src="/images/research/slope8.gif" alt="" width="180"/>
      <img src="/images/research/slope.gif" alt="" width="180"/>
      <img src="/images/research/slope9.gif" alt="" width="180"/><br>
      </center>
      <p> The pre-existing discontinuities in the jointed rock slopes play a key role in the slope stability, and the destabilization process often related to the complex interaction between the discontinuities and the intact rock bridge.
      <a href="https://www.sciencedirect.com/science/article/pii/S0266352X2200146X" target="_blank">Read more</a>.</p>
    <h3>Reservior slope under water fluncation</h3>
      <center>
      <img src="/images/research/slope10.gif" alt="" width="180"/>
      <img src="/images/research/slope11.gif" alt="" width="180"/>
      <img src="/images/research/slope12.gif" alt="" width="180"/>
      <img src="/images/research/slope10.png" alt="" width="190"/><br>
      Effects of water level change rates <br>
      <img src="/images/research/slope10.gif" alt="" width="180"/>
      <img src="/images/research/slope13.gif" alt="" width="180"/>
      <img src="/images/research/slope14.gif" alt="" width="180"/>
      <img src="/images/research/slope13.png" alt="" width="190"/><br>
      Effects of slope permeability coefficient  <br>
      </center>
      <p> Fluctuating water levels are responsible for many reservoir slope failures. Stability analysis of an ideal slope under reservoir water level fluctuation is analyzed, where the effect of reservoir fluctuation rate and rock permeability coefficient on slope stability are discussed.
      <a href="https://link.springer.com/article/10.1007/s11440-023-01895-4" target="_blank">Read more</a>.</p>
    
  <h3>Case study: Majiagou slope</h3>
    <center>
    <div style="width:66%;float:left;">
    <img src="/images/research/slopema.png" alt=""/>
    </div>
    <div style="width:34%;height:400px;float:left;">
    <img src="/images/research/slope29.gif" alt="" />
    <img src="/images/research/slope28.gif" alt="" />
    <img src="/images/research/slopema2.png" alt=""/><br>
    </div>
    </center>
    <p> Majiagou slope is a typical unstable bank slope influenced by the construction of the Three Gorges reservoir. A 150 m long, 5–10 cm wide crack at the slope crest developed within 3 months after the reservoir water level rose to 135 m in June 2003, and the slope deformation kept developing since then according to long-term monitoring.
    <a href="https://link.springer.com/article/10.1007/s11440-023-01895-4" target="_blank">Read more</a>.</p>
    <h3>Influence of earthquake</h3>
    <center>
    <img src="/images/research/slopesesimic.png" alt="" width="600"/><br>
    </center>
    <p> The dynamic stability of jointed rock slopes under seismic load is studied in this paper using FDEM. 
    <a href="https://www.sciencedirect.com/science/article/pii/S0266352X23003130#f0015" target="_blank">Read more</a>.</p>
  </div>
</div>
<hr>



<!-- Fluid flow -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchFlow">Flow and transport in fractured porous media</h2></center>
    <h3>Digital image based fluid flow model</h3>
    <center>
    <img src="/images/research/41.png" alt="" width="700"/><br>
    </center>
    <p> The presence of fractures in porous media strongly influences the fluid flow behavior. Accurately simulating the fluid flow in realistic fracture networks (compared to the statistical fracture networks) is still challenging due to the fracture complexity and computational burden. This work proposes a simple yet efficient numerical framework for the flow simulation in a lab-scale true triaxial hydraulically fractured shale sample with 3D high-resolution images, aiming at both computational accuracy and efficiency. 
    </p>

  <h3>Local grid refinement method</h3>
  <center>
  <img src="/images/research/42.png" alt="" width="700"/><br>
  </center>
  <p> 
  Local grid refinement (LGR) is adopted around the fracture to improve accuracy with lower computational burden. Results show that this method is efficient in capturing main phenomena of the fluid transport in fractured porous media, without sacrificing computational accuracy. Particularly, the convergence of the LGR is in a higher order than the global grid refinement (GGR). This model also provides great flexibility in handling a multitude of fracture input data, e.g., planar fractures obtained from statistical data and non-planar fractures from digital images represented with point clouds. Balancing computational accuracy and efficiency, this method provides an effective approach for simulating flow transport in fracture porous medium.
  <a href="https://www.sciencedirect.com/science/article/pii/S2352380823000746" target="_blank">Read more</a>.</p>
  </div>
</div>
<hr>



<!-- Thermal cracking -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchTC">Thermal cracking simulation</h2></center>
    <h3>TM coupled model</h3>
    <center>
    <div style="width:73%;float:left;">
    <img src="/images/research/TM0.png" alt=""/>
    </div>
    <div style="width:26%;height:400px;float:left;">
    <img src="/images/research/TM1.png" alt=""/>
    <img src="/images/research/TM2.gif" alt=""/>
    </div>
    </center>
   
  <h3>Anisotropoc model</h3>
  <center>
   <img src="/images/research/TM23.png" alt="" width="200" 
style="display:inline-block;vertical-align:top;"/>
<img src="/images/research/TM231.gif" alt="" width="195" 
style="display:inline-block;vertical-align:top;"/>
<img src="/images/research/TM232.gif" alt="" width="170" 
style="display:inline-block;vertical-align:top;"/>
<br> isotropic model <br>
<img src="/images/research/TM24.png" alt="" width="200" 
style="display:inline-block;vertical-align:top;"/>
<img src="/images/research/TM241.gif" alt="" width="195" 
style="display:inline-block;vertical-align:top;"/>
<img src="/images/research/TM242.gif" alt="" width="170" 
style="display:inline-block;vertical-align:top;"/>
<br> anisotropic model <br>
  </center>
  <p> We studied the heat transfer and thermal cracking process in the anisotropic shale formations based on the combined finite-discrete element method (FDEM).
  <a href="https://www.sciencedirect.com/science/article/pii/S0266352X19303015" target="_blank">Read more</a>.</p>

  <h3>Functionally graded materials</h3>
   <center>
   <img src="/images/research/TM31.png" alt="" width="300" 
style="display:inline-block;vertical-align:middle;"/>
   <img src="/images/research/TM311.gif" alt="" width="250" 
style="display:inline-block;vertical-align:middle;"/>
   <br>
   <img src="/images/research/TM32.png" alt="" width="300" 
   style="display:inline-block;vertical-align:middle;"/>
   <img src="/images/research/TM321.gif" alt="" width="250" 
   style="display:inline-block;vertical-align:middle;"/>
   <br>
   </center>
   <p> The functionally graded materials (FGMs), characterized by spatially varying material properties, have been used in a wide range of engineering applications (i.e., aerospace, nuclear reactor and microelectronics) in high temperature and high-temperature gradient environments. We investigated the thermal cracking process in FGMs under different kinds of thermal loads. 
   <a href="https://link.springer.com/article/10.1007/s40571-019-00290-9" target="_blank">Read more</a>.</p> 
<h3>Grain-based model</h3>
  <center>
  <img src="/images/research/52.png" alt="" width="600"/><br>
  </center>
  <p> Novel thermo-mechanical grain-based finite discrete element method approach was developed for thermal cracking in granitic rocks.
  <a href="https://link.springer.com/article/10.1007/s40948-022-00431-0" target="_blank">Read more</a>.</p>
<h3>Heating/-LN2 cooling treatment</h3>
 <center>
 <img src="/images/research/53.png" alt="" width="700"/><br>
 <img src="/images/research/GBM.png" alt="" width="150" 
style="display:inline-block;vertical-align:middle;"/>
 <img src="/images/research/GBM1.gif" alt="" width="120" 
style="display:inline-block;vertical-align:middle;"/>
 <img src="/images/research/GBM2.gif" alt="" width="120" 
style="display:inline-block;vertical-align:middle;"/>
 <img src="/images/research/GBM3.gif" alt="" width="120" 
style="display:inline-block;vertical-align:middle;"/>
 <img src="/images/research/GBM4.gif" alt="" width="120" 
style="display:inline-block;vertical-align:middle;"/>
 <img src="/images/research/GBM5.gif" alt="" width="120" 
style="display:inline-block;vertical-align:middle;"/>
 </center>
 <p>  Thermal treatment of the warm rock mass using liquid nitrogen (LN2) is a prospective rock fracturing technology in many geo-engineering applications. We present an experimental and numerical work aimed at investigating the effect of thermal treatments (i.e., heating–LN2 cooling) on fracture failure characteristics. results show that the thermal treatment has a significant influence on the fracture toughness and roughness. 
 <a href="https://link.springer.com/article/10.1007/s00603-022-02893-w" target="_blank">Read more</a>.</p> 
  </div>
</div>
<hr>



<!-- grouting -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchGrout">Grout migration</h2> </center>
      <h3>FDEM-grouting model</h3>
      <center>
      <img src="/images/research/grout1.png" alt="" width="400"/>
      <img src="/images/research/grout1.gif" alt="" width="160"/>
      <img src="/images/research/grouting.gif" alt="" width="210"/>
      <br>
      </center>
    <p> Grouting is a widely used geotechnical engineering method to improve the strength and reduce the hydraulic conductivity of rock masses. This FDEM-grouting can consider the HM coupling effect, the stress-induced fracture aperture variation, the fracture networks evolution and the hardening of grout during the grouting process.
    <a href="https://www.sciencedirect.com/science/article/pii/S0886779818301524" target="_blank">Read more</a>.</p>
      <h3>In-situ stress effect</h3>
      <center>
      <img src="/images/research/grouts1.png" alt="" width="600"/>
      <img src="/images/research/grouts2.png" alt="" width="600"/>
      <br>
      </center>
    <p> The grouting process is a typical coupled hydro-mechanical (HM) problem. The dilation process experienced by the fracture during grout injection clearly illustrates the necessity of considering the HM coupling effect. The effect of the in-situ stress conditions on the anisotropic grout penetration is properly modelled with the Y-grouting that, together with the stress interaction between neighbor fractures, explains why finer fractures are more difficult to be grouted and whether increasing the grouting pressure could be an effective way to improve the penetration in fine fractures. 
    <a href="https://doi.org/10.1016/j.ijrmms.2023.105392" target="_blank">Read more</a>.</p>
  </div>
</div>
<hr>


<!-- hydraulic fracturing -->
<div class="container">
  <div style="width:800px;text-align:justify;">
    <center><h2 id="ResearchHF">hydraulic fracturing</h2> </center>
      <h3>FEMM method</h3>
      <center>
      <img src="/images/research/J0.gif" alt="" width="180" style="display:inline-block;vertical-align:middle;"/>
      <img src="/images/research/J30.gif" alt="" width="160" style="display:inline-block;vertical-align:middle;"/>
      <img src="/images/research/J60.gif" alt="" width="160" style="display:inline-block;vertical-align:middle;"/>
      <img src="/images/research/multifrac.gif" alt="" width="200" style="display:inline-block;vertical-align:middle;"/><br>
      </center>
    <p> A discontinuous hybrid “FE-Meshfree” method is developed to simulate three-dimensional (3D) cracking. Compared to the extended finite element method (XFEM), the present hybrid “FE-Meshfree” method is not required to increase the size of global stiffness matrix, introduce extra unknowns, and construct special enrichment functions.
    <a href="https://link.springer.com/article/10.1007/s00603-018-1648-1" target="_blank">Read more</a>.</p>
      <h3>FDEM method</h3>
      <center>
      <img src="/images/research/HF1.png" alt="" width="80"/>
      <img src="/images/research/HF1.gif" alt="" width="75"/>
      <img src="/images/research/HF2.gif" alt="" width="75"/>
      <img src="/images/research/hf2.png" alt="" width="155"/>
      <br>
      <img src="/images/research/hf22.png" alt="" width="160" style="display:inline-block;vertical-align:top;"/>
      <img src="/images/research/hf22.gif" alt="" width="140" style="display:inline-block;vertical-align:top;"/>
      </center>
    <p> FDEM is developed to handle hydromechanical-fracture coupling problems and investigate the simultaneous multiple hydraulic fracturing mechanism.When multiple hydraulic fractures propagate simultaneously, there is an interaction effect among these propagating hydraulic fractures, known as the stress-shadow effect, which has a significant impact on the fracture geometry.
    <a href="https://www.hindawi.com/journals/geofluids/2018/4252904/" target="_blank">Read more</a>.</p>
  </div>
</div>
<hr>


<nbsp>
