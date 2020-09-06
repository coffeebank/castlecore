---
layout: page
navname: Vote

voteLinks:
  - name: MinecraftMP
    url: https://minecraft-mp.com/server/265546/vote/
    
  - name: MCServerTime
    url: https://mcservertime.com/server-wyscraft.87/vote

  - name: MCSL
    url: https://minecraft-server-list.com/server/465209/vote/

  - name: MinecraftServers
    url: https://minecraftservers.org/server/591327

  - name: PlanetMinecraft
    url: https://www.planetminecraft.com/server/wyscraft-dungeons-custom-items-mobs-economy-survival/vote/
    
  - name: MinecraftPEServers
    url: https://minecraftpocket-servers.com/server/103033/vote/

---

![Wyscraft server banner](/media/banner.png){:.mt-8}

# Voting Sites
{:.pt-4}

Please vote for Wyscraft to help support us and get an in-game reward!
MinecraftPEServers does not issue a reward.

<div id="voteLinks" class="flex flex-wrap items-start content-start pt-4 pb-8">
{% for vlink in page.voteLinks %}
<div class="w-full sm:w-auto mb-2 mr-1">
<a href="{{ vlink.url }}" target="_blank" rel="noopener">
<div class="button w-full sm:w-auto text-center sm:text-left" style="line-height:1.5"><span>{{ vlink.name }}</span></div>
</a>
</div>
{% endfor %}
</div>
