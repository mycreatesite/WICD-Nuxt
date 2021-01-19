<template>
    <footer>
        <p>
            © Copyright {{getYear}} │ Masayoshi Kawashima a.k.a. ma-ya’s CREATE All rights
            reserved.
        </p>
    </footer>
</template>

<script>
export default {
  computed: {
      getYear(){
          const date = new Date();
          return date.getFullYear();
      }
  }
};
</script>