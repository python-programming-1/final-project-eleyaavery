# final_project_summer_2019

@author: ramseyavery2
"""

def title():
    print ('        _               ______            _          _____       _     __          _______          _    __              __  ________ ')
    print ('       / \             |  ___ \          / \        |  ___ \    | |   / /         / ______|        / \   \ \            / / | _______|')
    print ('      / _ \            | |   \ \        / _ \       | |   \ \   | |  / /         / /              / _ \   \ \          / /  | |       ')
    print ('     / / \ \           | |    \ \      / / \ \      | |   / /   | | / /         / /              / / \ \   \ \        / /   | |____   ')
    print ('    / /___\ \          | |     | |    / /___\ \     | |__/ /    | |/ /         | |              / /___\ \   \ \      / /    | _____|  ')
    print ('   / _______ \         | |     | |   /  _____  \    |  ___ \    | |\ \         | |             / /_____\ \   \ \    / /     | |       ')
    print ('  / /       \ \        | |    / /   / /       \ \   | |   \ \   | | \ \         \ \           / /       \ \   \ \  / /      | |       ')
    print (' / /         \ \       | |___/ /   / /         \ \  | |    \ \  | |  \ \         \ \______   / /         \ \   \ \/ /       | |______ ')
    print ('/_/           \_\      |______/   /_/           \_\ |_|     \_\ |_|   \_\         \_______| /_/           \_\   \__/        |________|')
  


print (title ())


print ('You wake up in a dark cave with water dripping down the walls.')
print ('     ')
print ('There is a voice echoing through the cavern and into your head.')
print ('     ')
print ('It\'s me and before we continue I should probably introduce myself. I am your guide through the caves and I will prompt you with questions while you answer with yes/no or left/right.')
print ('     ')
print ('If you do not use these exact words your exploration will fail to work')
print ('     ')
print ('Alrighty then! Glad we are in agreement! Now to continue.')
print ('     ')
print ('There seem to be two hallways leading out of the cavern one to the right and one to the left.')
print ('     ')

end_game = 'END GAME'
left_vs_right = input('Which do you choose?')

if left_vs_right == 'left':
    vine = input('As you head down the path vines begin to cover the walls. Do you want to continue?')
    print (vine)
if left_vs_right == 'right' :
    stalagmite = input('As you go down the path stalagmites begin to gently glow protruding from cracks in the stone wall. Do you want to continue?')
    print (stalagmite)
    
#stalagmite = input('As you go down the path stalagmites begin to gently glow protruding from cracks in the stone wall. Do you want to continue?')
if stalagmite == 'yes' :
    crystal_cave = input ('The small tunnel opens up into a cavern so filled with crystals that it almost looks like a mirror maze. Do you want to continue further?')
    print (crystal_cave)
    print ('    /|\      ____ ')
    print ('   / | \    /|/__|')
    print ('  /_ |/|   / /  / ')
    print (' |   | |  / /  /  ')
    print (' |   | | / /  /   ')
    print (' |   | |/ /  /    ')
    print (' |   | | /  /     ')
    print (' |   | |/  /      ')
    print (' |__ |/___/       ')
    print (crystal_cave)
if stalagmite == 'no' :
   print ('I mean kinda weird but I guess we can stay here')
   print (end_game)
   
if crystal_cave == 'yes' :
    heat = input ('As you near the light the temperature gets hotter and hotter to the point where you are sweating and turning red. Do you want to retreat?')
    print (heat)
if crystal_cave == 'no' :
    print ('It is not the ugliest place we could have stopped')
    print (end_game)
    
if heat == 'yes' :
    print ('Really you\re just gonna give up at a little heat? Ugh fine.')
    print (end_game)
if heat == 'no' :
    lava = input ('You step into the next cavern and the heat is palpable and you look down at your feet noticing that you are standing on a huge shelf made completely out of obsidian. There seem to be some step-like carving on one side. Do you want to use them?')
    print (lava)
    
if lava == 'yes' :
    steps = input('You make your way slowly down the steps making sure each foot is as solid as possible before you put your weight on it. The heat immediatelly starts lifting as ou go further and further down and it is is once again cool and damp'
                  'The room you find yourself is absolutely filled with softly glowing butterflying swooping and swirling down a path to your right. Follow them?')
    print (steps)
if lava == 'no' :
    print ('Yeah no. I may just be a voice in your head but I am not about to die in the natural equivalent of a toaster oven. You\'re taking the steps.')
    butterflytunnel = input('You make your way slowly down the steps making sure each foot is as solid as possible before you put your weight on it. The heat immediatelly starts lifting as ou go further and further down and it is is once again cool and damp'
                  'The room you find yourself is absolutely filled with softly glowing butterflying swooping and swirling down a path to your right. Follow them?')
    print (steps)
    
if butterflytunnel == 'yes' :
    sandy = input ('The tunnel gets lighter and lighter until it is so bright the butterflies lose their glow completely and suddenly you come upon a set of very sandy steps that seem to lead out of the tunnel. Do you take them?')
if butterflytunnel == 'no' :
    print ('At least we aren\'t in the toaster oven.')
    print (end_game)

if sandy == 'no' :
    print ('Really? This is where you want to live the rest of your life? Your funeral man.')
    print (end_game)
if sandy == 'yes':
    print ('After climbing the stairs you find yourself in the middle of the La Canãda Watershed staring up at the sweltering California sun. You\'ve escaped')
    print (end_game)
    

#vine = input('As you head down the path vines begin to cover the walls. Do you want to continue?')   
if vine == 'yes':
    amazon = input ('The small tunnel opens up, overlooking a jungle rivaling the amazon. Do you want to climb down?')
    print ('              _           ')
    print ('        /\   / \  __      ')
    print ('        \ \  | | /  |     ')
    print ('         \ \ | |/  /      ')
    print ('          \ \| /  /       ') 
    print ('   _ _ _ _ \_\/__/_ _ _ _ ')
    print ('   \_ _ _ _|    |_ _ _ _ /')
    print ('          /|____|  \      ') 
    print ('         /  /| | \  \     ')
    print ('        /  / | |  \  \    ')
    print ('       |__/  | |   \__|   ') 
    print ('             \_/          ') 
    print (amazon)
if vine == 'no' :
    print ('You do know we are in a tunnel right? To each their own I guess.')
    print (end_game)
    
if amazon == 'yes' :
    lake_vs_jungle = input ('You slowly pick your way down the cliff side until you land on soft mossy grass. You see a short path winding into the jungle on the left and on the right you see a small glimmer indicating a body of water. Which way do you want to go?')
    print (lake_vs_jungle)
if amazon == 'no' :
    print ('It\'s not a bad place to stop.')
    print (end_game)

if lake_vs_jungle == 'left':
    hide_vs_run = input ('It\'s getting darker and darker the longer you move along the path and you are hearing low growling somewhere to the right of that seems to get closer and closer. Do you want to hide or run?')
    print (hide_vs_run)
if lake_vs_jungle == 'right' :
    wade_further = input ('As you near the water it just seems to grow and grow and when you put your hand into the water you find that it is pleasantly warm. Do you want to wade in further?')
    print (wade_further)
    
if wade_further == 'yes' :
    deeper = input ('you suddenly fall off the shelf of sand and slip under water. You desperately try to hold your breathe and kick back to the surface but you keep sinking. Finally you run out of air and inhale a deep gulp of water. However, you aren\'t drowning. You are just fine breathing in water steadily'
                    'you notice that all the fish are headed downwards toward a strange looking light. Do you follow them?')
    print (deeper)
if wade_further == 'no':
    print ('I don\'t mind settling down here. It is pretty peaceful afterall.')
    print (end_game)

if deeper == 'yes' :
    fish = input ('A gigantic brightly colored fish swims up close to you and seems to be nudging you, urging you to take hold of its fin. Do you take his fin?' )
    print (fish)
if deeper == 'no':
    sink = input ('It\'s no use. You just continue to sink. A gigantic brightly colored fish swims up close to you and seems to be nudging you, urging you to take hold of its fin. Do you take his fin?')
    print (sink)
    
if fish == 'yes' :
    print ('The fish picks up the pace moving quickly towards the light and you squeeze your eyes shut until you seem to feel yourself breaking the surface of a body of water.')
    print ('You frantically look around searching for the fish as you bob in the salty water and you notice that you are maybe only 20 feet away from the Santa Monica Pier.')
    print ('      ')
    print (end_game)
if fish == 'no' :
    print ('The fish swims off and you continue to sink towards the bright light albit at a slower pace than before and you just let the light envelope you.')
    print ('You feel yourself break through the surface of the water, gasping for air you didn\'t even need and notice that you are maybe 20 feet from Santa Monica Pier bobbing in ocean water')
    print ('    ')
    print (end_game)

if sink == 'yes' :
    print ('The fish picks up the pace moving quickly towards the light and you squeeze your eyes shut until you seem to feel yourself breaking the surface of a body of water.')
    print ('You frantically look around searching for the fish as you bob in the salty water and you notice that you are maybe only 20 feet away from the Santa Monica Pier.')
    print ('      ')
    print (end_game)
if sink == 'no' :
    print ('The fish swims off and you continue to sink towards the bright light albit at a slower pace than before and you just let the light envelope you.')
    print ('You feel yourself break through the surface of the water, gasping for air you didn\'t even need and notice that you are maybe 20 feet from Santa Monica Pier bobbing in ocean water')
    print ('    ')
    print (end_game)
    
if hide_vs_run == 'hide' :
    hide = input('You quickly duck behind a bush as what looks like a very large chinchilla ambles past you snuffling and growling. It seems to know where it is going. Do you want to follow it?')
    print (hide)
if hide_vs_run == 'run' :
    run = input('You take off, running for your life. Until you suddenly find yourself falling head over heels and hitting the ground. You just tripped over a root. Do you run or hide?')
    print (run)

if run == 'hide' :
    hide = input('You quickly duck behind a bush as what looks like a very large chinchilla ambles past you snuffling and growling. It seems to know where it is going. Do you want to follow it?')
    print (hide)
if run == 'run' :
    print ('Run where? You have no clue where you are going. Just go hide. You run and hide.')
    hide = input('You quickly duck behind a bush as what looks like a very large chinchilla ambles past you snuffling and growling. It seems to know where it is going. Do you want to follow it?')
    print (hide)
    
if hide == 'yes' :
    follow = input ('you follow the odd looking creature as it shuffles. It suddenly stops with its nose up in the air, slowly turning to face you. Do you freeze or play dead?')
    print (follow)
if hide == 'no' :
    print ('Well that\'s dumb. Where else are you gonna go? You\'re gonna follow it')
    follow = input ('you follow the odd looking creature as it shuffles. It suddenly stops with its nose up in the air, slowly turning to face you. Do you freeze or play dead?')
    print (follow)
    
if follow == 'freeze' :
    print ('It seems to chuff at you and turns around to come near you when suddenly you have a very large chinchilla rubbing its face against yours. It then indicates for you to climb up its back and hold on. You do and the chinchilla continues on its way' 
                    'through the jungle until you are breaking through the trees back into a tunnel and then finally onto a hill overlooking L.A.')
    print ('        ')
    print (' It gives one last nuzzle and makes its way back into the tunnels as you wave goodbye.')
    print (end_game)
    
if follow == 'play dead' :
    print ('It turns around and comes to sniff where you are laying nudging you with its nose. Panic is building in your chest and you try to stay as still as possible as it slowly picks you up by your shirt with its teeth and turns to trot on.')
    print ('     ')
    print (' You stay very still until you start to see light against the back of your eyelids and feel yourself being gently placed on the ground.')
    print (' It gives you a little nuzzle and you hear its footsteps fade away as it leaves. You sit up to look around and discover yourself looking down over L.A.')
    print (end_game)

    
    
    
