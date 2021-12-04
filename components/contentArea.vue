<template>
  <div>
    <div class="content-area">

        <div class="content-text">
            Unlock the event with your Ticket-ID. Please note that the Ticket-ID can only be activated once per account.
        </div>
        
        <div class="input-container-content">
            <label>
              <input class="input-content" placeholder="Enter Ticket-ID"/>
            </label>  
        </div>
    </div>  
        <div class="input-button-content">
          <NuxtLink
            to="/" 
            class="input-button"
          >
            Primary
          </NuxtLink>
        </div>
  </div>
</template>

<style>
  @import './../assets/styles/contentArea.css';
</style>
