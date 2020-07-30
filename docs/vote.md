---
layout: page
navname: Vote

voteLinks:
  - name: MCServerTime
    url: https://mcservertime.com/server-wyscraft.87/vote

  - name: MCSL
    url: https://minecraft-server-list.com/server/465209/vote/

  - name: MinecraftServers
    url: https://minecraftservers.org/server/591327

  - name: PlanetMinecraft
    url: https://tinyurl.com/wysccvote4

---

# Voting Sites
Please vote for Wyscraft to help support us and get an in-game reward!

<div id="voteLinks" class="flex flex-wrap items-start content-start py-4">
{% for vlink in page.voteLinks %}
<div class="w-full sm:w-auto mb-2 mr-1">
<a href="{{ vlink.url }}" target="_blank" rel="noopener" class="button">{{ vlink.name }}</a>
</div>
{% endfor %}
</div>
