<template>
  <div>
    <a
      href="../assets/files/SalmaResume.pdf"
      download="SalmaResume.pdf"
      class="download-button"
    >
      <Icon name="mdi:arrow-collapse-down" class="mr-2" />
      Download My Resume
    </a>
  </div>
</template>


<style scoped>
.download-button {
  display: inline-flex;
  align-items: center;
  padding: 0.5rem 1rem; /* py-2 px-4 */
  background-color: #2563eb; /* bg-blue-600 */
  color: #ffffff; /* text-white */
  font-weight: bold; /* font-bold */
  border-radius: 9999px; /* rounded-full */
  transition: background-color 0.3s ease-in-out; /* transition duration-300 ease-in-out */
}

.download-button:hover {
  background-color: #1d4ed8; /* hover:bg-blue-700 */
}
</style>