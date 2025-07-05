<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import MegaphoneIcon from './icons/IconMegaphone.vue'
import HeadsetIcon from './icons/IconHeadset.vue'
import EaselIcon from './icons/IconEasel.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>

  <WelcomeItem>
    <template #icon>
      <HeadsetIcon />
    </template>
    <template #heading>Technical Consulting</template>

    I help you design and implemented tech systems that empower people, not just processes. From cloud-native to AI, 
    I make technology approachable, impactful, and tailored to your mission, whether you are a solo entrepreneur, a non-profit, a small business or a large enterprise.
    <ul>
      <li>Kubernetes Deployment & Monitoring</li>
      <li>Serverless Deployment & Monitoring</li>
      <li>OpenTelemetry Deployment & Monitoring - Spans, Traces, Logs & Metrics</li>
      <li>Architectural Diagrams</li>
      <li>Implementation & Enablement</li>
    </ul>
    <a href="https://khc-solutions.webflow.io" target="_blank" rel="noopener">View my pricing options</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Design</template>

    I create digital designs for <b>Print on Demand (POD)</b> products, as well as <b>websites, flyers, business cards, infographics</b> etc.
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Visit KHC Studio for POD designs</a> | 
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">View my graphic designs on Behance</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <MegaphoneIcon />
    </template>
    <template #heading>Public Speaking & Podcasts</template>

    I am available to speak at conferences, panels, meetups, school events etc on a variety of topics, but mainly focused on Women in Tech, Black in Tech and Immigrant workers in Tech. 
    <br><br>I've spoken at ACT-W's virtual conference and have done podcasts with Uncut Women and PurePerformance.
    <a href="https://speakerhub.com/speaker/kayan-hales" target="_blank" rel="noopener">Book me for an event</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Notary</template>

    I am a notary certified by the State of Michigan, but I do remote notarizations for other states + MI through Blue Notary.
    <a href="https://app.bluenotary.us/notary/invite?signingType=ron" target="_blank" rel="noopener">Set up a notary session with me</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Community</template>

    I do believe in our work being most fruitful when the people around us benefit. Visit these local orgs that I volunteer with based in Detroit, MI.
    <ul>
      <li><a href="https://math4success.org" target="_blank" rel="noopener">Math4Success</a></li>
      <li><a href="https://microsoftteals.com" target="_blank" rel="noopener">Microsoft Teals</a></li>
      <li><a href="https://blackgirlscode.org" target="_blank" rel="noopener">BlackGirlsCode</a></li>
      <li><a href="https://sisterscode.org" target="_blank" rel="noopener">SistersCode</a></li>
    </ul>
  </WelcomeItem>

  
</template>
