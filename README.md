# 137-MHz-V-Dipole-for-Weather-Satellites

This is a simple v-dipole for use with weather satellites around 137MHz, such as the new METEOR M2-3.  This antenna is designed to be more rugged and easier to build accurately than some of the current designs out there.  The durability will be beneficial for a permanent installation, or, in the case of a temporary install, will help avoid damage during setup and storage.  The total cost should be around $30, depending on what's in your scrap bin.

The two unique features of this project are the 3D printed housing, and the NiCopp tubing.  The 3D printed housing allows for the 120 degree angle beween the two halves of the dipole to be accurately established and consistently maintained.  It also provides environmental protection to the soldered connection between the coax and the antenna elements.  The NiCopp tubing is designed for automotive use in corrosive environments, so it shouldn't care much about rain.  It is about 89% copper, 9% nickel, and 2% other stuff.  This makes it very resistant to corrosion and easy to solder to with regular 60/40 rosin core solder.

<b>Materials Needed</b>
<ul>
  <li>42" of AGS NiCopp 3/8" Tubing</li>
    <ul>
      <li>Available at your local auto parts store, it is commonly used for brake lines and fuel lines.</li>
      <li>You need two 21" lengths.</li>
      <li>Part numbers would be CN530, CN540, CN551, CN560, CN572, with the last two digits being the length in inches.  For example, CN551 is 51" long.</li>
    </ul>
  <li>PETG Filament and a 3D Printer</li>
  <li>Silicone Adhesive</li>
  <li>Your choice of coax, up to RG-6 size, but try to use something with a copper braid</li>
  <li>Optionally, two #110 o-rings and one o-ring that fits around your coax</li>
  <li>3 each 8-32x1" Nylon Screws</li>
    <ul>
      <li>Metal screws would probably work just fine too</li>
    </ul>
</ul>

<b>Assembly Instructions</b>
<ol>
  <li>Print both halves and the tubing end caps</li>
    <ul>
      <li>I used PETG and have not had issues with the summer heat yet.</li>
      <li>PLA may work in a mild climate, but is not tested.</li>
    </ul>
  <li>Run an 8-32 tap down each hole on the bottom half of the 3D printed housing.</li>
  <li>Use a tubing cutter to cut two 21" sections of the 3/8 tubing</li>
  <li>Use a dremel cutoff wheel to notch the end of the tubing as shown.</li>
    <ul>
      <li>The exact dimensions of this notch are not critical and only serve to make soldering easier.</li>
    </ul>
      
![20230711_165844](https://github.com/thetoivonen/137-MHz-V-Dipole-for-Weather-Satellites/assets/18183123/f8382be0-340d-47e8-aa1c-1313e00fc6b7)

    
  <li>"Tin" the inside of the tubing, where the coax will be attached.</li>
  <li>If using an o-ring on your coax, slide in on now and push it out of the way.
  <li>Strip your coax and tin the ends of the braid and the center conductor.
    <ul>
      <li>I am using LMR-195 in these photos.</li>
      <li>The 3D printed block is designed to handle up to RG-6 size coax.</li>
      <li>If you want to use RG-6, crimp a copper ferrule to the aluminum braid so it can be soldered to the tubing.</li>
        <ul>
          <li>I am aware of the impedance mismatch if RG-6 is used, it's a topic for another day.</li>
        </ul>
    </ul>
  </li> 
  <li>Solder the coax to the tubing before placing in the 3D printed housing.</li>

![20230711_170438](https://github.com/thetoivonen/137-MHz-V-Dipole-for-Weather-Satellites/assets/18183123/c0fa392c-bddb-4be8-a0e5-dfa700cffc87)
  
  <li>If you are using o-rings, slip them on the tubing and coax.</li>
  <li>Place silicone sealant in the groove around the 3D printed housing, in the o-ring cavities, and where the coax will sit.  Do this on both halves. </li>
  <li>Lay the tubing and coax in place, followed by the top half, and install the screws.  I used a c-clamp to gently hold the two halves together while I installed the screws. </li>

![20230711_171335](https://github.com/thetoivonen/137-MHz-V-Dipole-for-Weather-Satellites/assets/18183123/3d977a86-16d5-4b84-a8ce-92e920d2c5de)

  <li>Install whatever connector you're going to use on the other end of your coax.</li>
  <li>Install and test.  If you want to you can use an antenna analyzer to fine tune the length, but if you don't have one don't worry about it, it'll be close enough.</li>
    <ul>
      <li>Remember the coax should ideally run horizontally away and perpendicular from the antenna for at least 21" before going in a different direction.  You can experiment to see how much this really matters.</li>
    </ul>
  <li>Don't forget to install the end caps, they aren't just for looks, but to keep bugs and water out of the tubing.</li>
</ol>
