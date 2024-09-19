document.getElementById('supportForm').addEventListener('submit', function(e) {
    e.preventDefault();

    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    // Zastąp poniższą sekcję kodem wysyłającym dane do serwera lub e-maila
    document.getElementById('status').textContent = 'Dziękujemy za kontakt, skontaktujemy się z Tobą wkrótce.';
});
