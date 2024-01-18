<!DOCTYPE html>
<html>
<script>
  var password = "69passwords";
  (function promptPass() {
    var psw = prompt("Enter your Password");
    while (psw !== password) {
      alert("Incorrect Password");
    }
  }());
  alert('Correct Password\nWelcome!');
</script>

<button onclick = "promptPass()" > Click Me </button>
</html>