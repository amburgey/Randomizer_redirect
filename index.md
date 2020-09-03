<script>
    // An array of URL's
    var randURLs = [
        "https://docs.google.com/forms/d/e/1FAIpQLSdsMhBGZt8qvkCoMIQZlQ6YHQaqjGz4-97nWYHdOFYvSKjUbg/viewform?usp=sf_link",
        "https://docs.google.com/forms/d/e/1FAIpQLSfCy8vhIKwXlbYpC95KRaXVZtpiTFh03KYK5mbwYR609U6eHw/viewform?usp=sf_link",
        "https://docs.google.com/forms/d/e/1FAIpQLSfcehbLeMJWvb43ZXxSb1sjL8inNQc_lj_FEBfUzGOhKoHahA/viewform?usp=sf_link"
    ];
    var randURL = Math.floor(Math.random() * randURLs.length);
    window.location=randURLs[randURL];
</script>
