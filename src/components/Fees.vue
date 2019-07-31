<template>
<div class="paycomponents">
    <p><img src="../assets/tuition-and-fees.png"/><span class="fees">STUDENT FEES</span></p>
    <div class="studentfees"> 
    <div class="invoiced">
        <p class="invoice">Invoice</p>
        <p class="number">₦2,300,000.00</p>
        <p class="blue">
            <center><img src="../assets/approve-invoice.png" class="box"/></center></p>    
    </div>

    <div class="invoiced">
        <p class="invoice">Recieved</p>
        <p class="number">₦1,700,000.00</p>
        <p class="green">
            <center><img src="../assets/recieved.png" class="boximg"/></center></p>   
    </div>

    <div class="invoiced">
         <p class="invoice">Pending</p>
        <p class="number">₦600,000.00</p>
        <p class="yellow">
            <center><img src="../assets/pendings.png" class="boximg"/></center></p>   
    </div>
    </div>
</div>
</template>


<style>
    .paycomponents {
        margin-left: 280px;
        margin-top: -690px;
    }
    .studentfees {
         display: flex;
    }
    .fees {
        margin-left: 10px;
        color: #3B3B3B;
        font-size: 10px;
    }
    .invoiced {
        width: 360px;
        height: 90px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 4.71062px 23.5531px rgba(0, 0, 0, 0.07);
        border-radius: 4.71062px;
        margin-right: 20px;
    }
    .invoice {
        font-weight: 600;
        font-size: 10px;
        line-height: 16px;
        display: flex;
        align-items: flex-end;
        text-transform: uppercase;
        color: #BDBDBD;
        margin-left: 20px;
        margin-top: 10px;
    }
    .number {
        font-family: Lato;
        font-style: normal;
        font-weight: normal;
        font-size: 24px;
        display: flex;
        align-items: flex-end;
        color: #1C75BB;
        margin-left: 20px;
        margin-top: -10px;
    }
    .blue {
        width: 75px;
        height: 75px;
        background: #1C75BB;
        border-radius: 4.71px;
        float: right;
        margin-top: -78px;
        margin-right: 20px;
    }
    .green {
        width: 75px;
        height: 75px;
        background: #17BF5F;
        border-radius: 4.71px;
        float: right;
        margin-top: -78px;
        margin-right: 20px;
    }
    .yellow {
        width: 77px;
        height: 77px;
        background: #FAD961;;
        border-radius: 4.71px;
        float: right;
        margin-top: -78px;
        margin-right: 20px;
    }
    .box {
        margin-top: 20px;
    }
</style>
