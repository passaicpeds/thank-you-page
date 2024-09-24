<div style="text-align:center;">
    <h1>Thank you!</h1>
    <p>Your submission has been received.</p>
    <img src="https://cdcssl.ibsrv.net/ibimg/smb/864x117_80/webmgr/21/2/x/Passaic-Pediatrics_Logo-1.webp?7e56b5ce9515709be776552e5d82fc0f" alt="Thank You Image" style="max-width:100%; height:auto;"> <!-- Insert the image here -->
    <p>This page will redirect in <span id="timer"></span>s.</p>
</div>

<script type="text/javascript">
var count = 5; // The delay in seconds before redirecting.
var redirect = "https://www.passaicpeds.com/forms-and-policies"; // The redirection's landing page.
function countDown() {
if(count >= 0){
document.getElementById("timer").innerHTML = count--;
setTimeout("countDown()", 1000);
}else{
window.location.href = redirect;
}
}
countDown();
</script>
