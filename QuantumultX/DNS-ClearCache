const message = {
    action: "dns_clear_cache"
};

$configuration.sendMessage(message).then(resolve => {
    if (resolve.ret) {
        console.log("成功刷新DNS!");
    } else {
        console.log(resolve.error);
    }
    $done();
}, reject => {
    $done();
});
