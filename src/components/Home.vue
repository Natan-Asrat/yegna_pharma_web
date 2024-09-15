<template>
    <div class="container mt-5">
        <div class="row">
          <!-- Hero Section (Left Column) -->
          <div class="col-md-6 d-flex flex-column justify-content-center">
            <h1 class="display-4">Yegna Pharma</h1>
            <p class="lead">
            Easily manage and track sales, inventory, and drug listings while monitoring revenue in real time. Streamline your workflow, reduce manual errors, and gain valuable insights into your business—all from one powerful and user-friendly platform.
             </p>
                    <a href="/YegnaPharmaLite.exe" target="_blank" download onclick="showFallback('setup')">
                <img src="/download.png" alt="Download Setup" class="img-fluid mt-3" style="max-width: 50%;"/>
                </a>
                
            <p id="fallback-setup" class="fallback-message" style="display: none;">
            If the download doesn't start, <a href="/YegnaPharmaLite.exe" target="_blank">click here</a> to download the setup.
            </p>
            <br>
            <p class="lead">
                Default user: John, Password: default
             </p>
    
          </div>
    
          <!-- Screenshots Section (Right Column) -->
          <div class="col-md-6">
          <div class="row">
              <div class="col-12 mb-4 justify-content-between screenshots">
                <img src="/login_background.jpg" alt="Screenshot 1" class="img-fluid screenshot screenshot-t"/>
              </div>
            
            </div>
          </div>
          
        </div>
        <div class="row">
            <div class="col-12 mb-4 justify-content-between screenshots">
                <img src="/dashboard_profile.jpg" alt="Screenshot 3" class="img-fluid screenshot-w screenshot-t"/>
              </div>
            </div>
          
            <div class="row">
            <div class="col-12 mb-4 justify-content-between screenshots">
                <img src="/Inventory.jpg" alt="Screenshot 3" class="img-fluid screenshot-w screenshot-t"/>
              </div>
            </div>

            <div class="row">
            <div class="col-12 mb-4 justify-content-between screenshots">
                <img src="/list_of_drugs.png" alt="Screenshot 3" class="img-fluid screenshot-w screenshot-t"/>
              </div>
            </div>
          
      </div>

    
</template>
    
    
    <style scoped>
    /* Optional: Add custom styles here */
    .hero-section {
      text-align: left;
    }
    
    .screenshot {
      max-width: 100%;
      height: auto;
    
    }
    
    .screenshot-t {
        margin-top: 50px;
    }
    .screenshot-b {
        margin-top: -50px;
    }
    .phone-mockup {
      position: relative;
      display: inline-block;
      width: 100%;
      max-width: 400px; /* Adjust based on the phone mockup size */
    }
    
    .phone-image {
      width: 100%;
      height: auto;
    }
    
    .screenshots {
      position: relative;
    }
    
    .screenshot-w{
      height: auto;
      width: 80%;
      margin-left: 20px;
      object-fit: fit;
      margin-bottom: 10px; /* Adjust spacing between screenshots */
      border-radius: 10px; /* Optional: Rounded corners for screenshots */
    }
    
    .screenshot {
      height: auto;
      width: 50%;
      margin-left: 20px;
      object-fit: fit;
      margin-bottom: 10px; /* Adjust spacing between screenshots */
      border-radius: 10px; /* Optional: Rounded corners for screenshots */
    }
    
    @media (max-width: 767px) {
      .screenshot {
      height: auto;
      width: 200px;
      object-fit: fit;
      margin-bottom: 10px; /* Adjust spacing between screenshots */
      border-radius: 10px; /* Optional: Rounded corners for screenshots */
      }
      .screenshot-t {
        margin-top: 20px;
    }
    .screenshot-b {
        margin-top: 20px;
    }
    }
    </style>
    
