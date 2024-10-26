---
layout: page
title: "Projects"
permalink: /projects/
---

<div class="project-card">
    <h3>Project Title 1</h3>
    <button onclick="toggleDetails('project1')">View Details</button>
    <div id="project1" class="project-details" style="display: none;">
        <p>Description of Project 1, tools used, results, etc.</p>
    </div>
</div>

<div class="project-card">
    <h3>Project Title 2</h3>
    <button onclick="toggleDetails('project2')">View Details</button>
    <div id="project2" class="project-details" style="display: none;">
        <p>Description of Project 2, tools used, results, etc.</p>
    </div>
</div>

<script>
function toggleDetails(id) {
    const details = document.getElementById(id);
    details.style.display = details.style.display === "none" ? "block" : "none";
}
</script>

<style>
.project-card {
    border: 1px solid #ccc;
    padding: 16px;
    margin: 8px 0;
    background-color: #f9f9f9;
    border-radius: 5px;
}
.project-details {
    margin-top: 10px;
    font-size: 0.9em;
}
</style>
