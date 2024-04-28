<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>About</template>
    <code class="m-0 p-0 text-dark text-lg">Hello World</code><br>
    Currently undertaking the KIEP-SKIES program at TUM. <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>
    <code class="text-primary">Frontend > HTML, CSS(Bootstrap 5, Tailwind CSS), JS(React)</code> <br />
    <code class="text-primary">Backend > SQL(MySQL, PostgreSQL), Py(Django, Flask)</code> <br />
    <code class="text-primary">DevOps > Git, CI/CD, Docker, Cloud(AWS), Linux</code>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Projects</template>

    Find my projects at:
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">School Management System</a>,
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">Events Management System</a>,
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">Tours & Travel Management System</a>, and
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">E-Commerce</a>.
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Work</template>
    "  The power of first impressions cannot be underestimated, and the gateway to capitalizing on them lies in exceptional website design. "
    Check out my GitHub...

    <!-- Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official
    Discord server, or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. You should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world. -->
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>

    Raech out through:
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">Email</a>,
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">LinkedIn</a>,
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">Slack</a>, or
    <a href="https://github.com/Gad-Ongoro" target="_blank" rel="noopener">WhatsApp</a>.
  </WelcomeItem>
</template>
