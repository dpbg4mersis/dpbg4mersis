new moto, Float:x, Float:y,Float:z;

GetPlayerPos(playerid, x, y, z);

moto = CreateVehicle(522, x,y,z,0.0,1,3,-1);

PutPlayerInVehicle(playerid, moto, 0);
