<script lang="ts">
    export let name: string ;
    let number = 0 ;
    export function incrementCount() {
    number += 1;
}
</script>

<button on:click={incrementCount}>{name} pressed the Button {number} times </button>

<style>
    button{
      border: 0.1;
      cursor: pointer;
      border-radius: 6px;
      padding: 8px 10px;
      font-weight: bold;
      box-shadow: 1px 2px 3px rgba(58, 57, 57, 0.2);
      background-color: rgb(128, 226, 246);
    }
    button:hover {
    background-color: #A78BFA;
    
    }
    

  </style>