<template>
  <!-- Generator: Adobe Illustrator 19.2.1, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
  <svg
    version="1.1"
    id="Layer_1"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink"
    x="0px"
    y="0px"
    width="15px"
    height="15px"
    viewBox="0 0 15 15"
    style="enable-background: new 0 0 15 15"
    xml:space="preserve"
  >
    <path
      :fill="fillColor(color)"
      d="M12.7,2.3v10.4H2.3V2.3H12.7 M13,1H2C1.4477,1,1,1.4477,1,2v11c0,0.5523,0.4477,1,1,1h11c0.5523,0,1-0.4477,1-1V2
	C14,1.4477,13.5523,1,13,1L13,1z"
    />
  </svg>
</template>

<script>
export default {
  props: {
    color: {
      type: String,
      default: "green",
    },
  },
  computed: {
    fillColor() {
      return (color) => {
        switch (color) {
          case "slate":
            return "#868686";
          default:
            return color;
        }
      };
    },
  },
};
</script>

<style></style>
