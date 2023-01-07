<template>
  <div>
    <Hero
      title='Become a member'
      sub-title='We are glad that you have chosen to become a member of the Transnational Community Federation e. V., a non-governmental and non-profit organization (TCF hereinafter). You are joining a heterarchical community and by that, you are making it stronger and more diverse. In order to find your place among the members and member organizations and in order for us to do the formal work of registering you as a part of the ecosystem, please answer the following questions. By submitting your membership request through this form you agree to our constitution and our data protection policy. We usually process the incoming membership requests within two weeks upon their arrival.'
    />
    <MembershipForm />
  </div>
</template>
<script>
import Hero from '../../components/sections/Hero'
import MembershipForm from '../../components/sections/membershipForm'
export default {
  name: 'membership',
  components: { MembershipForm, Hero }
}
</script>
