# OpenHAB-exporter-importer
OpenHAB REST Export/Import for Items and Links
<div>
		This page will allow you to make <b>all</b> your <i>items</i> editable (RW) in a couple of minutes. It doesn't matter if <i>items</i> are created in <a href="/paperui/" target="_blank">PaperUI</a>, <a href="/habmin/" target="_blank">HabMIN</a>, <i>.items</i>-files. <b>All</b> <i>items</i> will be inserted into the OpenHAB <b>JSON dB</b> and editable through <b>PaperUI</b>.<br>
		The main purpouse is adding <a href="https://www.openhab.org/docs/ecosystem/google-assistant/#google-assistant-action" target="_blank"><i>tags</i></a> enabling <a href="https://community.openhab.org/t/howto-listen-talk-to-your-home" target="_blank">Google Home</a> (and likely <a href="https://community.openhab.org/t/solved-easy-way-to-link-alexa-to-openhab" target="_blank">Alexa</a>?).<br>
	</div>
	<div>This is for RaspberryPi, OpenHab 2 (snapshot), SSH. It probably works for most platforms as long as you can SSH.<br>
		I'm using OH2 <a href="https://www.openhab.org/docs/installation/linux.html#file-locations" target="_blank">aliases</a> mapped to <i>/srv/</i> instead of hard paths, which makes it less platform dependent.
	</div>
	<div>
		The boring stuff: <b>"Use it at your own risk!"</b> I have +200 <i>items</i> and used this method 20 times now, rebooted plenty, tested again... but it may behave differently at your system.
	</div>