<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evidence Search</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #e0f7fa; /* Soft light blue background */
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
        }
        h1 {
            text-align: center;
            font-size: 2.5em;
            color: #00796b; /* Teal color for the heading */
            margin-bottom: 20px;
        }
        input[type="text"] {
            width: calc(100% - 22px);
            padding: 12px;
            margin-bottom: 10px;
            border: 2px solid #00796b; /* Teal border */
            border-radius: 5px;
            font-size: 1em; /* Slightly larger text for readability */
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #00796b; /* Teal button */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em; /* Slightly larger text for readability */
        }
        button:hover {
            background-color: #004d40; /* Darker teal on hover */
        }
        .quote-display {
            margin-top: 20px;
            font-size: 1.2em; /* Main font size */
            color: #333;
        }
        .quote-item {
            margin-bottom: 15px;
            padding: 10px;
            border-left: 4px solid #00796b; /* Teal left border */
            background-color: #f1f8e9; /* Light greenish background for quotes */
            border-radius: 5px; /* Rounded corners for quote items */
        }
        .quote-text {
            font-weight: bold; /* Bold text for quotes */
        }
        .quote-explanation,
        .quote-technique,
        .quote-themes {
            margin-top: 5px; /* Space between elements */
            font-size: 0.9em; /* Smaller font size for technique and themes */
            color: #555; /* Slightly darker grey for readability */
        }
    </style>
</head>
<body>

<div class="container">
    <h1>MSND Evidence Finder</h1>
    <input type="text" id="quoteInput" placeholder="Enter Themes, Character Name, Relationships ">
    <button onclick="displayQuotes()">Search</button>
    
    <div class="quote-display" id="quoteDisplay"></div>
</div>

<script>
    // Arrays to store quotes and their themes
    const quotes = [
        { 
            text: "Like to a step-dame or a dowager", 
            themes: ["theseus", "love","hippolyta-theseus", "simile", "all"], 
            explanation: "Love is akin to inheritence held back by an unyielding guardian. Transactional and tied to power dynamics",
            technique: "Simile"
        },
        { 
            text: "like to a silver bow/ New bent in heaven", 
            themes: ["hippolyta", "marrige","love", "hippolyta-theseus","simile", "imagery","all"], 
            explanation: "Love celestial & uplifting. Foil between Hippolyta and Theseus's perspective on love. Tension",
            technique: "Imagery/Simile"
        },
        { 
            text: "bewitched", 
            themes: ["diction", "patriarchy", "all"], 
            explanation: "Disobediance attributed to supernatural causes",
            technique: "Diction"
        },
        { 
            text: "With feighing voice verses of feighning love ", 
            themes: ["love", "egeus", "all", "fricative"], 
            explanation: "|f| sound gives the impression that Egeus is spitting on him",
            technique: "Repetition & Fricatives"
        },
        { 
            text: "as a form in wax", 
            themes: ["patriarchy", "hermia-egeus", "simile", "all"], 
            explanation: "identity and choices are malleable, she has limited agency in face of her father's sexpectations and societal norms. Vulnerability, how external factors shape personal identity. no free will, creator's control over what it has created. ",
            technique: "Simile"
        },
        { 
            text: "barren sister", 
            themes: ["metaphor", "patriarchy", "all"], 
            explanation: "Celibate women devoid of purpose. value linked to ability to bera children & fulfill traditional roles of wives & mothers",
            technique: "Metaphor"
        },
        { 
            text: "earthlier happy is the rose distilled ... withering on the virgin thorn", 
            themes: ["metaphor", "patriarchy", "all"], 
            explanation: "withering, loss of vitality and purpose. satisfying male demands gives women fullfillment, like being distilled into sweet perfume. ",
            technique: "Metaphor"
        },
        { 
            text: "spotted and inconstant man", 
            themes: ["demetrius", "unfaithfulness", "metaphor","all"], 
            explanation: "Demetrius has tendancy to be unfaithful. moral blemishes.",
            technique: "Metaphor"
        },
        { 
            text: "fit your fancies to your father's will", 
            themes: ["fricative", "patriarchy", "all"], 
            explanation: "pressurised to harmonise her own desires to her father's will. firmness of authority. sense of friction, fit, forced alignment, suppressing her own desires",
            technique: "Fricative"
        },
        { 
            text: "How chance the roses there do fade so fast?...tempest of my eyes", 
            themes: ["metaphor", "love", "hermia" ,"hermia-lysander","all"], 
            explanation: "lysander is perceptive observing and showing concern. Being away from lover, causes Hermia Anguish. She is distressed - which is uncharacteristic of her, she was calm in Theseus's court.",
            technique: "Metaphor"
        },
        { 
            text: "swift as shadow, short as any dream", 
            themes: ["simile", "love", "foreshadow", "all"], 
            explanation: "Meaningful and powerful while it lasts much like an emotionally charged dream. Like shadows can transform into different forms. Lysander despite knowing this chooses to elope with Hermia. Foreshadows future obstacles that are awaiting them.",
            technique: "Simile & Foreshadow"
        },
        { 
            text: "H: too high to be enthralled to low L: Or else misgraffed in respect of years - H: O spite! too old to be engaged to young", 
            themes: ["stiychpmythia", "antithesis","love","hermia-lysander", "all"], 
            explanation: "Can easily pick up eachother's lines, meant to be, in love. Antithesis shows common obstacles thwarting love, none of which apply to hermia & lysander. They seem well suited to eachother, audience feels pained as to why these two can't be together.",
            technique: "Stichomythia & Antithesis"
        },
        { 
            text: "jaws of darkness do devour it up", 
            themes: ["metaphor", "love", "all"], 
            explanation: "Love can be injurious, savour it while it lasts. Deespite knowing this Lysander chooses to love Hermia. ",
            technique: "Metaphor"
        },
        { 
            text: "Chanting faint hymns to the cold fruitless moon", 
            themes: ["imagery", "patriarchy", "all"], 
            explanation: "Emotional detachment. Theseus trying to scare her from celibate life. Hermia brave. Stigma attached to leading celibate lives. ",
            technique: "Auditary Imagery"
        },
        { 
            text: "the fire which burned the Carthage queen .. Cupid's strongest bow .. Venus' doves ", 
            themes: ["allusion", "love", "all"], 
            explanation: "reckless devotion, love all encompassing, powerful, romantic intensity ",
            technique: "Allusion"
        },
        { 
            text: "earthlier happy is the rose distilled ... withering on the virgin thorn", 
            themes: ["metaphor", "patriarchy", "all"], 
            explanation: "withering, loss of vitality and purpose. satisfying male demands gives women fullfillment, like being distilled into sweet perfume. ",
            technique: "Metaphor"
        },
        { 
            text: "earthlier happy is the rose distilled ... withering on the virgin thorn", 
            themes: ["metaphor", "patriarchy", "all"], 
            explanation: "withering, loss of vitality and purpose. satisfying male demands gives women fullfillment, like being distilled into sweet perfume. ",
            technique: "Metaphor"
        },
        
    {
        text: "The course of true love never did run smooth.",
        themes: ["love", "challenges", "relationships", "all", "relation", "character", "theme", "technique"],
        explanation: "True love always encounters difficulties, like social status, adding to the play's chaotic, comedic events.",
        technique: "Metaphor"
    },
    {
        text: "Love looks not with the eyes, but with the mind; / And therefore is winged Cupid painted blind.",
        themes: ["love", "appearance vs reality", "perception", "all", "relation", "character", "theme", "technique"],
        explanation: "Love prioritizes inner qualities over looks; Cupid's blindness illustrates love as irrational, defying logic and reason.",
        technique: "Metaphor"
    },
    {
        text: "Though she be but little, she is fierce!",
        themes: ["gender", "helena", "strength", "defiance", "all", "relation", "character", "theme", "technique"],
        explanation: "Despite size, women possess strength, defying societal expectations and stereotypes, showcasing inner power and resilience.",
        technique: "Characterization"
    },
    {
        text: "If we shadows have offended, / Think but this, and all is mended, / That you have but slumbered here / While these visions did appear.",
        themes: ["dreams", "illusion", "reality", "forgiveness", "all", "relation", "character", "theme", "technique"],
        explanation: "The play's events may be a dream, prompting audience forgiveness and blurring reality with illusionary experiences.",
        technique: "Metaphor"
    },
    {
        text: "I would my father looked but with my eyes.",
        themes: ["desire", "perception", "family", "all", "relation", "character", "theme", "technique"],
        explanation: "Hermia desires her father's understanding, wanting him to perceive the world from her unique perspective.",
        technique: "None"
    },
    {
        text: "So quick bright things come to confusion.",
        themes: ["fate", "confusion", "mortality", "all", "relation", "character", "theme", "technique"],
        explanation: "This emphasizes the fleeting nature of beauty and joy, highlighting the rapid decline of positive things.",
        technique: "None"
    },
    {
        text: "Ill met by moonlight, proud Titania.",
        themes: ["conflict", "supernatural", "pride", "all", "relation", "character", "theme", "technique"],
        explanation: "Oberon's confrontation with Titania establishes their rivalry and sets the stage for ensuing supernatural conflicts.",
        technique: "None"
    },
    {
        text: "I'll put a girdle round about the earth / In forty minutes.",
        themes: ["magic", "power", "supernatural", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck's boast highlights his magical abilities and extraordinary speed, showcasing his powerful supernatural nature.",
        technique: "Imagery"
    },
    {
        text: "I love thee not, therefore pursue me not.",
        themes: ["rejection", "unrequited love", "hate", "all", "relation", "character", "theme", "technique"],
        explanation: "Demetrius bluntly rejects Helena's love, expressing his disinterest and discouraging her persistent pursuit of him.",
        technique: "None"
    },
    {
        text: "I am your spaniel: And, Demetrius, / The more you beat me, I will fawn on you.",
        themes: ["obsession", "unrequited love", "helena", "all", "relation", "character", "theme", "technique"],
        explanation: "Helena's comparison to a spaniel underscores her intense devotion, willing to endure mistreatment for Demetrius' affection.",
        technique: "Simile"
    },
    {
        text: "I know a bank where the wild thyme blows, / Where oxlips and the nodding violet grows.",
        themes: ["nature", "beauty", "oberon", "all", "relation", "character", "theme", "technique"],
        explanation: "Oberon's description creates a vivid image of a beautiful, natural place, rich with flowers and wild plants.",
        technique: "Imagery"
    },
    {
        text: "To say the truth, reason and love keep little company together nowadays.",
        themes: ["love", "reason", "bottom", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom observes that logical thought and emotional feelings rarely coexist, especially within romantic relationships and decisions.",
        technique: "None"
    },
    {
        text: "Lord, what fools these mortals be!",
        themes: ["mortals", "folly", "puck", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck's exclamation expresses his amusement and disdain for the foolish behavior and decisions of humans.",
        technique: "None"
    },
    {
        text: "She was a vixen when she went to school: / And though she be but little, she is fierce!",
        themes: ["helena", "strength", "defiance", "all", "relation", "character", "theme", "technique"],
        "explanation": "Helena portrays Hermia as spirited and tenacious despite her small stature, revealing her defiant and feisty nature.",
        technique: "Characterization"
    },
    {
        text: "Jack shall have Jill. / Nought shall go ill.",
        themes: ["resolution", "order", "puck", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck's rhyme summarizes the play's resolution, suggesting everything will conclude happily and without further complications or problems.",
        technique: "Repetition"
    },
    {
        text: "My Oberon! What visions have I seen! / Methought I was enamour’d of an ass.",
        themes: ["dreams", "transformation", "titania", "all", "relation", "character", "theme", "technique"],
        explanation: "Titania describes her dream of being in love with an ass, showcasing the bizarre effects of magic.",
        technique: "Imagery"
    },
    {
        text: "Are you sure / That we are awake? It seems to me / That yet we sleep, we dream.",
        themes: ["reality", "dreams", "demetrius", "all", "relation", "character", "theme", "technique"],
        explanation: "Demetrius questions their waking state, blurring the line between reality and dream, creating uncertainty for the characters.",
        technique: "None"
    },
    {
        text: "I have had a most rare vision. I have had a dream, / past the wit of man to say what dream it was.",
        themes: ["dreams", "bottom", "imagination", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom struggles to articulate the extraordinary and incomprehensible nature of his recent and fantastical dream experience.",
        technique: "None"
    },
    {
        text: "This is the silliest stuff that ever I heard.",
        themes: ["performance", "comedy", "hippolyta", "all", "relation", "character", "theme", "technique"],
        explanation: "Hippolyta expresses her disapproval of the play's absurdity, finding the performance to be ridiculous and nonsensical overall.",
        technique: "None"
    },
    {
        text: "I am sent with broom before, / To sweep the dust behind the door.",
        themes: ["order", "puck", "cleaning", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck metaphorically describes his role in restoring order by cleaning up messes and resolving conflicts within the play.",
        technique: "Metaphor"
    },
    {
        text: "I must go seek some dewdrops here, And hang a pearl in every cowslip's ear.",
        themes: ["nature", "fairy", "beauty", "all", "relation", "character", "theme", "technique"],
        explanation: "A fairy's task showcases the beauty of nature by embellishing cowslips with dewdrops, creating a magical scene.",
        technique: "Imagery"
    },
    {
        text: "Bless thee, Bottom! Bless thee! Thou art translated.",
        themes: ["transformation", "bottom", "quince", "all", "relation", "character", "theme", "technique"],
        explanation: "Quince reacts with awe to Bottom's physical transformation, blessing and acknowledging his altered state during the play.",
        technique: "None"
    },
    {
        text: "What angel wakes me from my flow’ry bed?",
        themes: ["awakening", "titania", "beauty", "all", "relation", "character", "theme", "technique"],
        explanation: "Titania, awakening in a flower-covered bed, describes her surrounding with rich and beautiful visual details.",
        technique: "Imagery"
    },
    {
        text: "Cupid is a knavish lad, Thus to make poor females mad.",
        themes: ["love", "cupid", "puck", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck blames Cupid for causing madness in women, attributing their irrational behavior to Cupid's mischievous nature.",
        technique: "None"
    },
    {
       text: "Love's stories written in love's richest books. To fan the moonbeams from his sleeping eyes.",
        themes: ["love", "romance", "lysander", "all", "relation", "character", "theme", "technique"],
        explanation: "Lysander evokes romance and love stories, painting imagery of moonlit nights, conveying deep love.",
        technique: "Imagery"
    },
    {
        text: "O, when she's angry, she is keen and shrewd! She was a vixen when she went to school",
        themes: ["anger", "helena", "strength", "all", "relation", "character", "theme", "technique"],
        explanation: "Helena's sharp wit and intelligence come to the forefront when angry, displaying her strength when challenged.",
        technique: "None"
    },
    {
        text: "Two lovely berries moulded on one stem.",
        themes: ["friendship", "hermia", "helena", "all", "relation", "character", "theme", "technique"],
        explanation: "Hermia describes her friendship with Helena as inseparable, comparing them to berries, highlighting their close and intertwined relationship.",
        technique: "Simile"
    },
    {
        text: "Thus I die. Thus, thus, thus.",
        themes: ["death", "performance", "bottom", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom's melodramatic delivery in Pyramus’ death scene uses repetition, exemplifying comedic acting within the play.",
        technique: "Repetition"
    },
    {
        text: "The best in this kind are but shadows, and the worst are no worse, if imagination amend them.",
        themes: ["imagination", "performance", "theseus", "all", "relation", "character", "theme", "technique"],
        explanation: "Theseus notes that imagination can improve even the worst performances, emphasizing the theater's illusory nature.",
        technique: "Metaphor"
    },
     {
        text: "I am your spaniel; and, Demetrius, The more you beat me, I will fawn on you.",
        themes: ["love", "helena", "demetrius", "all", "relation", "character", "theme", "technique"],
        explanation: "Helena's devotion, she compares herself to a dog willing to endure mistreatment from Demetrius, indicating her submissive love.",
        technique: "Simile"
    },
    {
        text: "I know a bank where the wild thyme blows",
        themes: ["nature", "oberon", "all", "relation", "character", "theme", "technique"],
        explanation: "Oberon's description evokes a vivid scene, highlighting nature's tranquility, beauty, and wild setting through imagery.",
        technique: "Imagery"
    },
    {
        text: "Are you sure That we are awake? It seems to me That yet we sleep, we dream.",
        themes: ["reality", "demetrius", "dreams", "all", "relation", "character", "theme", "technique"],
        explanation: "Demetrius' words showcase uncertainty, questioning whether they are experiencing reality or if are still sleeping, emphasizing unreality.",
        technique: "None"
    },
    {
       text: "Methought I was enamoured of an ass",
        themes: ["love", "titania", "transformation", "all", "relation", "character", "theme", "technique"],
        explanation: "Titania recounts her dream, revealing being in love with an ass, representing absurd love due to magic.",
        technique: "Imagery"
    },
     {
        text: "The eye of man hath not heard, the ear of man hath not seen, man's hand is not able to taste, his tongue to conceive, nor his heart to report, what my dream was",
        themes: ["imagination", "bottom", "dreams", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom struggles to articulate what is dream with repetition, showcases the indescribable nature of imagination.",
        technique: "Repetition"
    },
    {
        text: "Love's stories written in love's richest books",
        themes: ["love", "lysander", "stories", "all", "relation", "character", "theme", "technique"],
        explanation: "Lysander talks of love stories metaphorically, expressing love is complex, diverse like stories in books.",
        technique: "Metaphor"
    },
    {
        text: "Reason and love keep little company together nowadays",
        themes: ["love", "reason", "bottom", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom highlights the conflict of logic and emotion, pointing out reason and love don't coincide currently.",
        technique: "None"
    },
    {
        text: "She was a vixen when she went to school",
        themes: ["helena", "anger", "strength", "all", "relation", "character", "theme", "technique"],
        explanation: "Helena’s description reveals a strong personality, showcasing sharpness, shrewdness since childhood, demonstrating character strength.",
        technique: "None"
    },
    {
        text: "To say the truth, reason and love keep little company together nowadays.",
        themes: ["love", "reason", "bottom", "all", "relation", "character", "theme", "technique"],
        explanation: "Bottom highlights a modern truth, as love and reason rarely align, creating conflict and irrational decisions.",
        technique: "None"
    },
    {
        text: "If we shadows have offended",
        themes: ["forgiveness", "puck", "performance", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck's plea for forgiveness if performance caused offense, linking play's illusions and inviting audience’s clemency.",
        technique: "Metaphor"
    },
    {
        text: "I am sent with broom before, To sweep the dust behind the door.",
        themes: ["order", "puck", "cleaning", "all", "relation", "character", "theme", "technique"],
        explanation: "Puck's duty represents the restoration of harmony, sweeping conflicts symbolically removing disorder, enhancing closure.",
        technique: "Metaphor"
    },


        
   

        
        
   
]

    ;

    function displayQuotes() {
        const input = document.getElementById('quoteInput').value.toLowerCase();
        const quoteDisplay = document.getElementById('quoteDisplay');
        
        // Split input into an array of themes and trim whitespace
        const themes = input.split(',').map(theme => theme.trim());

        // Filter quotes based on the entered themes
        const filteredQuotes = quotes.filter(quote => 
            quote.themes.some(quoteTheme => themes.includes(quoteTheme.toLowerCase()))
        );
        
        // Clear previous results
        quoteDisplay.innerHTML = "";

        // Display relevant quotes or a message if none found
        if (filteredQuotes.length > 0) {
            filteredQuotes.forEach(quote => {
                const quoteElement = document.createElement('div');
                quoteElement.className = 'quote-item';
                
                quoteElement.innerHTML = `
                    <div class="quote-text">"${quote.text}"</div>
                    <div class="quote-explanation">Explanation: ${quote.explanation}</div>
                    <div class="quote-technique">Technique Used: ${quote.technique}</div>
                
                `;
                
                quoteDisplay.appendChild(quoteElement);
            });
        } else {
            quoteDisplay.textContent = "No quotes found for these themes.";
        }
    }
</script>

</body>
</html>
