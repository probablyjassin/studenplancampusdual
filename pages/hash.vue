<template>
	<div class="min-h-screen flex-col md:flex-row gap-5 flex items-center justify-center">
		<div class="p-8 rounded shadow-md w-full max-w-md bg-secondary">
			<h1 class="text-primary text-xl font-bold mb-4">Wie finde ich mein Passwort (Hash)?</h1>
			<p class="text-text mb-4">
				Der Hash der für CampusDual wie ein Passwort funktioniert, ist in den URL-Parametern der Anfragen enthalten. 
                Drücke CTRL+Shift+I um die Konsole zu öffnen und öffne unter "Netzwerk" die Anfrage. <br><br>
                Diesen Hash benutzt du hier im Login als Passwort. <br>
                Dieser setzt sich wenn überhaupt selten zurück, also muss er nicht jedes mal neu geholt werden!
			</p>
		</div>
		<div class="w-full md:w-1/2">
			<img src="/images/hash.webp" class="object-cover rounded w-full" />
		</div>
	</div>
</template>

<script>
	export default {
		name: "HashPage",
	};
</script>

<style scoped>
	/* Add any additional styles here */
</style>
