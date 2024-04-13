
document.addEventListener("DOMContentLoaded", function() {
    const form = document.getElementById("contact-me-section");
    const rateInput = document.getElementById("hourly-rate");

    // Function to toggle visibility of hourly rate input based on selected option
    function toggleHourlyRateInput() {
        if (document.querySelector('input[name="reason"]:checked').value === "Hiring") {
            rateInput.style.display = "block";
            rateInput.setAttribute("required", true);
        } else {
            rateInput.style.display = "none";
            rateInput.removeAttribute("required");
        }
    }

    // Event listener for radio buttons to toggle hourly rate input
    document.querySelectorAll('input[name="reason"]').forEach((radio) => {
        radio.addEventListener("change", toggleHourlyRateInput);
    });

   // Event listener for form submission
document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contact-form');
    form.addEventListener('submit', function(event) {
        event.preventDefault(); 
        
        if (validateForm()) {
            form.submit(); 
        }
    });
});

    // Function to validate form fields
    function validateForm() {
        let isValid = true;

        // Validate each input field
        const nameInput = document.getElementById("name");
        const emailInput = document.getElementById("email");
       
        if (nameInput.value.trim() === "") {
            isValid = false;
            nameInput.classList.add("error");
        } else {
            nameInput.classList.remove("error");
        }

        //validation for email format
        const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
        if (!emailRegex.test(emailInput.value.trim())) {
            isValid = false;
            emailInput.classList.add("error");
        } else {
            emailInput.classList.remove("error");
        }

        return isValid;
    }
});
