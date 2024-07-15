<script setup>
  import ExpandBox from './components/ExpandBox.vue';
  const title = 'minha caixa'
  const caixa = [
{ id: 1 , title: 'caixa1', content: 'conteudo-1', quatity: 100},
{id: 2, title: 'caixa 2'},
{id: 3, title: 'caixa 3', quatity : 50},
{id: 1, title: 'caixa 4', content: 'conteudo secreto 4'}
  ]
</script>

<template>
  <div>
    <expand-box :title="title" />
   <!---- <expand-box title="Título da caixa de expansão " content="segredo" />
    <expand-box title="Título da caixa de expansão 2"  />
    <expand-box title="Título da caixa de expansão 3" quantity="20"  /> --->
  </div>
</template>