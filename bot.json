var Discord = require('discord.io');
var logger = require('winston');
var auth = require('./auth.json');

// Configure logger settings
logger.remove(logger.transports.Console);
logger.add(new logger.transports.Console, {
    colorize: true
});
logger.level = 'debug';

// Initialize Discord Bot
var bot = new Discord.Client({
   token: auth.token,
   autorun: true
});

bot.on('ready', function (evt) {
    logger.info('Connected');
    logger.info('Logged in as: ');
    logger.info(bot.username + ' - (' + bot.id + ')');

bot.on('message', function (user, userID, channelID, message, evt) {

    if (message.substring(0, 1) == '!') {
        var args = message.substring(1).split(' ');
        var cmd = args[0];
       
        args = args.splice(1);
        switch(cmd) {
	// !hi
            case 'hi':
                bot.sendMessage({
                    to: channelID,
                    message: 'Hello! Do you how do?'
                });
            break;

	// !hello
            case 'hello':
                bot.sendMessage({
                    to: channelID,
                    message: 'Hello! Do you how do?'
                });
            break;

	// !bye
            case 'bye':
                bot.sendMessage({
                    to: channelID,
                    message: 'Adios, amigos!'
                });
            break;

	// !boo
            case 'boo':
                bot.sendMessage({
                    to: channelID,
                    message: 'Ahh!'
                });
            break;

	// !do-you-how-do?
            case 'do-you-how-do?':
                bot.sendMessage({
                    to: channelID,
                    message: 'I\'m *bot* bad! Get it?'
                });
            break;

	// !how-are-you?
            case 'how-are-you?':
                bot.sendMessage({
                    to: channelID,
                    message: 'I\'m *bot* bad! Get it?'
                });
            break;

	// !frick
            case 'frick':
                bot.sendMessage({
                    to: channelID,
                    message: '*Gasp* NO!'
                });
            break;

	// !achoo
            case 'achoo':
                bot.sendMessage({
                    to: channelID,
                    message: 'Bless you!'
                });
            break;

            

	// !Elliott
            case 'Elliott':
                bot.sendMessage({
                    to: channelID,
                    message: '*dreamy sigh*'
                });
            break;


	// !
            case '':
                bot.sendMessage({
                    to: channelID,
                    message: ''
                });
            break;

























//self help

            
	// !I-Self-cared
            case 'I-self-cared':
                bot.sendMessage({
                    to: channelID,
                    message: 'I\'m so gosh darn proud of you!'
                });
            break;



	// !Self Harm Help
            case 'twsh':
                bot.sendMessage({
                    to: channelID,
                    message: 'TW: ||Hmm... I know a great website that might help: https://becausewecandothistogether.tumblr.com/alternativesforselfharm ||'
                });
            break;

            // !Breathing Exercises
            case 'twbe':
                bot.sendMessage({
                    to: channelID,
                    message: '4, 7, 8! Oh! Here, try this: https://media1.giphy.com/media/BCPirjGS76yVG/source.gif'
                });
            break;

            // !Suicidal Thoughts
            case 'twst':
                bot.sendMessage({
                    to: channelID,
                    message: 'TW || No, no, no, you are so very loved! Oh, no, don\'t go away! Here, maybe this will help: https://thoughtcatalog.com/erin-cossetta/2018/03/50-reasons-to-live/||'
                });
            break;





//Episodes
	// !Cartoon Therapy 1
            case 'CT1':
                bot.sendMessage({
                    to: channelID,
                    message: 'We are the Crystal Gems! Hehe, here ya go: https://www.youtube.com/watch?v=DSPEZ6GAnzA'
                });
            break;

	// !Cartoon Therapy 2
            case 'CT2':
                bot.sendMessage({
                    to: channelID,
                    message: 'BRAINBLAST! Coming up: https://www.youtube.com/watch?v=XX-zZSiwzpc'
                });
            break;


	// !My True Identity!
            case 'SS-MTI':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/S9xPOCk91mc'
                });
            break;

	// !WAY TOO ADULT
            case 'SS-WTA':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/mttAIWkjqoI'
                });
            break;

	// !Taking on ANXIETY!!
            case 'SS-TOA':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/rjMxXTCGPu8'
                });
            break;

	// !A New Year Of Lying To Myself!!
            case 'SS-ANYOLTM':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/XQbzcEBsEbA'
                });
            break;

	// !The Dark Side Of Disney!
            case 'SS-TDSOD':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/opYHx1lSAB0'
                });
            break;

	// !I'M IN A DISNEY SHOW!!
            case 'SS-IIADS':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/gCl3ku0G8b0'
                });
            break;

	// !The MIND vs. The HEART!
            case 'SS-TMVTH':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/oyqrqfH-pAY'
                });
            break;

	// !Alone on VALENTINE'S DAY!
            case 'SS-AOVD':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/7rVlwIdanms'
                });
            break;

	// !Losing My Motivation
            case 'SS-LMM':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/tXvAHDpmrHI'
                });
            break;

	// !Sanders Sides Q&A
            case 'SS-Q&A':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/HhwMZQAI1cc'
                });
            break;

	// !Am I Original?
            case 'SS-AIO':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/3FguTMzvdsc'
                });
            break;

	// !My NEGATIVE Thinking
            case 'SS-MNT':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/m-z0Q8Y9rLI'
                });
            break;

	// !Growing Up
            case 'SS-GU':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/p_Pi-RAA34Q'
                });
            break;

	// !Making Some Changes!
            case 'SS-MSC':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/K6ZnRPMDjg8'
                });
            break;

	// !Becoming a CARTOON!
            case 'SS-BAC':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/--rJwJuXuOI'
                });
            break;

	// !ACCEPTING ANXIETY, Part 1/2: Excepting Anxiety!
            case 'SS-AA1':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/Ndk9JXKci4g'
                });
            break;

	// !ACCEPTING ANXIETY, Part 2/2: Can Anxiety Be Good?
            case 'SS-AA2':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/wr17Kq5bmtI'
                });
            break;

	// !Fitting In (Hogwarts Houses!)
            case 'SS-FI':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/Soy5mOEXA2Q'
                });
            break;

	// !MOVING ON, Part 1/2: Exploring Nostalgia
            case 'SS-MO1':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/ihCqpkPNtNM'
                });
            break;

	// !MOVING ON, Part 2/2: Dealing With A Breakup
            case 'SS-MO2':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/m-PMR1TDMQk'
                });
            break;

	// !The Sanders Sides 12 DAYS OF CHRISTMAS!
            case 'SS-12DOC':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/6rg2Y_S057M'
                });
            break;

	// !Can LYING Be Good?
            case 'SS-CLBG':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/N2d4oti_eBo'
                });
            break;

	// !Why Do We Get Out of Bed in the Morning?
            case 'SS-WDWGOOBITM':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/N8h1LiMTGR0'
                });
            break;

	// !Crofters - The MUSICAL!
            case 'SS-CTM':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/njdGXAcdTeg'
                });
            break;

	// !Learning New Things About Ourselves
            case 'SS-LNTAO':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/-tkqsuZx1n8'
                });
            break;

	// !EMBARASSING PHRASES: The Nightmare Instead Of Christmas!
            case 'SS-TNIOC':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/VjwlmNjEK8w'
                });
            break;

	// !Selfishness v. Selflessness
            case 'SS-SVS':
                bot.sendMessage({
                    to: channelID,
                    message: 'https://youtu.be/iauvHYa21G8'
                });
            break;




	// Just add any case commands if you want to..
         }
	}	
})
});