---
layout: post
title: New post to show Stace
subtitle: Testing page
---

Hello there!

**bold** and *italics* and 

# H1 is this

## H2 is this

---

<a href="#pop">Push to dataLayer</a>

<script>
  // Wait until the DOM is fully loaded.
  document.addEventListener('DOMContentLoaded', function() {
    // Get the link element.
    var link = document.getElementById('datalayerLink');

    // Add a click event listener to the link.
    link.addEventListener('click', function(event) {
      // Stop the link from behaving in the default way.
      event.preventDefault();

      // Push an event to the dataLayer.
      window.dataLayer = window.dataLayer || [];
      window.dataLayer.push({
        'event': 'customEventName',
        'customKey': 'customValue'
      });
    });
  });
</script>



adkjcbasjfwdkjf wekjfe 
cew ckjnckjewqc

qckjwqbckjq

svjdfnbdwjnd
 
 
 