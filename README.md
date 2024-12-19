.header {
    background-color: #0C4A60; /* Set header color */
    color: #FFFFFF; /* Optional: Set text color for better contrast */
    padding: 20px; /* Add some padding */
    height: 80px; /* Set a fixed height for the header */
    display: flex; /* Use flexbox for alignment */
    align-items: center; /* Center items vertically */
}
.nav-link {
    display: inline-block; /* Make the link behave like a block element */
    padding: 10px 20px; /* Add padding for a button-like appearance */
    border-radius: 25px; /* Make the corners rounded */
    background-color: #F1A260; /* Set the background color */
    color: #FFFFFF; /* Set text color to white for contrast */
    transition: background-color 0.3s ease, transform 0.3s ease; /* Add transition for smooth effect */
    text-decoration: none; /* Remove underline from links */
}

.nav-link:hover {
    background-color: #D89A4D; /* Darker shade for hover effect */
    transform: scale(1.05); /* Slightly scale up on hover */
