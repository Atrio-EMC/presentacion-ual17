---
layout: presentacion
title: Programando infraestructura en la nube
tema: serif
---
<section>
  <h2>Programando infraestructura en la nube</h2>
  <h4>IV Jornadas de Informática de la UAL</h4>
  <small>
    <a href="http://albertomolina.wordpress.com">Alberto Molina Coballes</a> y
    <a href="http://www.josedomingo.org">José Domingo Muñoz Rodríguez</a>
  </small>
  <p>
    <a href="http://creativecommons.org/licenses/by-sa/3.0/">
      <img src="img/cc_by_sa.png" width="100px" border="0"/></a>
  </p>
  <p><small>Theme by: <a href="http://lab.hakim.se/reveal-js/#/">reveal.js</a></small></p>
</section>
<section>
<section>
  <h3>La nube (Cloud Computing)</h3>
  <p>El cloud computing o computacion en la nube es una nuevo paradigma que permite ofrecer servicios de computación de forma ágil y sencilla a través de la red.</p>
  <h4>¿Qué servicios podemos obtener de la nube?</h4>
</section>
<section>
  <h3>SaaS</h3>
  <ul>
    <li></li>
  </ul>
</section>
<section>
  <h3>PaaS</h3>
  <ul>
    <li></li>
  </ul>
</section>
<section>
  <h3>IaaS</h3>
  <ul>
    <li></li>
  </ul>
</section>
<section>
  <q style="margin-bottom: 1em;">El SaaS lo podemos programar, en el PaaS podemos programar. <em>¿Se puede programar la ingraestructura?</em>
</section>
</section>


<section>
  <q style="margin-bottom: 1em;">La automatización es en informática el conjunto de métodos que
    sirven para realizar tareas repetitivas en un ordenador</q>
  <br />
  
  <ul>
    <li>La automatización es cada vez más habitual en entornos de
      infraestructura clásica (máquinas físicas o virtuales)</li>
    <li>La automatización es <strong>obligatoria</strong> en
      entornos de IaaS donde los elementos se crean y eliminan a
      demanda de forma muy rápida</li>
  </ul>
</section>
<section>
  <h3>¿Qué automatizar?</h3>
  <ul>
    <li>Aprovisionamiento de recursos</li>
    <li>Configuración de los recursos</li>
    <li>Respuestas ante eventos</li>
  </ul>
</section>
<section>
  <h3>Herramientas genéricas</h3>
  <ul>
    <li>Shell scripts</li>
    <li>Aplicación en un lenguaje de alto nivel. APIs</li>
    <li>Bibliotecas de despliegue: Capistrano o Fabric</li>
    <li>Herramientas de gestión de la configuración:
      <ul>
	<li>Puppet</li>
	<li>Chef</li>
	<li>Ansible</li>
	<li>Salt (SaltStack)</li>
      </ul>
    </li>
    <li>O mejor aún: combinando varios de ellos</li>
  </ul>
</section>
<section>
  <h3>cloud-config</h3>
  <ul>
    <li>Configura una instancia a partir de los parámetros del
      servidor de metadatos</li>
    <li>Se configuran en la opción "User data" de Portal o en "Script
      personalizado" de Horizon</li>
    <li>Utilizado en otras nubes públicas y privadas
    <li>La aplicación más utilizada es cloud-init, desarrollado por
    Canonical</li>
  </ul>
</section>
<section>
  <h3>Orquestación</h3>
  <ul>
    <li>En cloud computing se refiere a la posibilidad de gestionar de
      forma automática el aprovisionamiento, la configuración e incluso
      la respuesta a eventos</li>
    <li>Específicamente utilizando herramientas propias</li>
    <li>El componente de OpenStack encargado de la orquestación se
      denomina heat</li>
    <li>Amazon CloudFormation</li>
    <li>OASIS Topology and Orchestration Specification for Cloud
      Applications (TOSCA)</li>
  </ul>
</section>
    
