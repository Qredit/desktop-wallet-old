<template>
  <div class="Links w-full h-full overflow-none bg-theme-feature rounded-lg p-10">
    <h3>Links</h3>
    <div class="Announcements__line-separator mt-6" />
    <h3>Node Rest API</h3>
    <br>
    <div>Use our API’s to interact with the Qredit blockchain. You can develop or test your own tools on the Qredit blockchain.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://qredit.io/restapidocs/');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>Block Explorer</h3>
    <br>
    <div>The Block Explorer allows you to search for transactions, delegates and wallets. You can also check the stability of our network.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://explorer.qredit.io');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>Qredit Wiki</h3>
    <br>
    <div>All Qredit related tutorials and how-to’s in one place.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://docs.qredit.io');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>Qredit Network</h3>
    <br>
    <div>Voting for a delegate. Here you can find and select a delegate.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://qredit.network');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>Qredit Vote Report</h3>
    <br>
    <div>A detailed delegate Vote Report.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('http://qredit.world-domination.org/');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>Buy or Sell Qredit</h3>
    <br>
    <div>Qredit is actively traded on the Altilly Exchange. Click on the button below to visit the Altilly Exchange.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://www.altilly.com/market/XQR_BTC');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
    <div class="Announcements__line-separator mt-6" />
    <h3>About Qredit and Hodler Enterprises</h3>
    <br>
    <div>Learn more about Hodler Enterprises, the company behind Qredit.</div>
    <br>
    <button
      class="red-button cursor-pointer inline-flex items-center self-stretch refresh-button mr-2 py-2 px-4 rounded mr-2 px-3 py-2"
      @click="electron_openExternal('https://hodler.enterprises/project/qredit/');"
    >
      <br>
      <h4>
        <span style="color: #fff;">
          Click here!
        </span>
      </h4>
    </button>
  </div>
</template>

<script>
</script>
