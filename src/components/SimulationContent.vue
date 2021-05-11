<template>
    <div class="simulasi-container grid col-auto p-0 m-0">
        <div class="simulasi-container-horizontal grid text-white text-left font-bold m-1 p-0 align-middle text-xs lg:text-xl">
            <p>Komponen</p>
            <p>Nama Komponen</p>
            <p>Harga</p>
            <p>Marketplace</p>
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>CPU</p>
            <div class="komp-selection">
                <label for="cpu"></label>
                    <select id="cpu" name="cpulist" form="cpuform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>Motherboard</p>
            <div class="komp-selection">
                <label for="motherboard"></label>
                    <select id="motherboard" name="motherboardlist" form="motherboardform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>Memory</p>
            <div class="komp-selection">
                <label for="memory"></label>
                    <select id="memory" name="memorylist" form="memoryform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>  
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>Graphics Card</p>
            <div class="komp-selection">
                <label for="graphicsCard"></label>
                    <select id="graphicsCard" name="graphicsCardlist" form="graphicsCardform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>Power Supply</p>
            <div class="komp-selection">
                <label for="powerSupply"></label>
                    <select id="powerSupply" name="powerSupplylist" form="powerSupplyform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>Case</p>
            <div class="komp-selection">
                <label for="case"></label>
                    <select id="case" name="caselist" form="caseform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div> 
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>SSD 1</p>
            <div class="komp-selection">
                <label for="ssd"></label>
                    <select id="ssd" name="ssdlist" form="ssdform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div> 
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>SSD 2</p>
            <div class="komp-selection">
                <label for="ssd"></label>
                    <select id="ssd" name="ssdlist" form="ssdform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div> 
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>HDD 1</p>
            <div class="komp-selection">
                <label for="hdd"></label>
                    <select id="hdd" name="hddlist" form="hddform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div> 
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>HDD 2</p>
            <div class="komp-selection">
                <label for="hdd"></label>
                    <select id="hdd" name="hddlist" form="hddform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        <div class="simulasi-container-horizontal text-xs lg:text-xl">
            <p>HDD 3</p>
            <div class="komp-selection">
                <label for="hdd"></label>
                    <select id="hdd" name="hddlist" form="hddform">
                        <option value="komp1">komponen 1</option>
                        <option value="komp2">komponen 2</option>
                    </select>
            </div>
            <p>Rp.x.xxx.xxx</p>
            <button class="beli-btn">Beli Sekarang</button> 
        </div>
        </div>
        <button class="saveBuild-btn text-black w-full h-12 bg-green1 my-5 text-center inline-block text-xl cursor-pointer ">Save Build</button> 
</template>

<script>
export default {

}
</script>

<style scoped>

.simulasi-container-horizontal{
    grid-template-columns: 20% 40% 20% 20%;
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
}

.simluasi-boldtext{
    font-weight: 700;
}

.komp-selection option, .komp-selection select{
    background-color: black;
    color: white;
    border: none;
    width: 95%;
    height: 100%;
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
    /* font-size: 18px; */
}

.simulasi-container-horizontal{
    display: grid;
    grid-template-columns: 20% 40% 20% 20%;
    color: white;
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
    /* font-size: 18px; */
    text-align: left;
    margin: 0;
    padding: 0;
    vertical-align: middle;
    align-items: center;
}

.beli-btn{
    border: none;
    color: black;
    width: 100%;
    height: 70%;
    background-color: #02F39B;
    margin: 1rem 0;
    padding: 3px 0;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    cursor: pointer;
    /* font-size: 20px; */
}

</style>