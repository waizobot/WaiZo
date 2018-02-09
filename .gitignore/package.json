const Discord = require('discord.js');

var bot = new Discord.Client();
var prefix = ("/");

bot.on('ready', ()=>{
    console.log("Bot Ready !");
});

bot.login('NDExNTY5MzEzNzIwMzAzNjI4.DV-NpQ.jb4gsSh4dt7pSdP071Z7ehlhfmI');

bot.on('message', message => {
    if (message.content === "ça va WaiZo"){
        message.reply("oui et toi");
        console.log('ça va WaiZo oui et toi');
    }

    if (message.content === prefix + "help"){
        message.channel.sendMessage("voici les commandes du bot :\n -help pour afficher les commandes \n -music pour la musique \n -modération pour les commandes de modérations \n -méteo pour la méteo");
        console.log("commande help demandée !");
    }
});
