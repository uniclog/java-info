>  

Optional

boolean temp = Optional.ofNullable(devices)
.map(it -> it.stream().anyMatch(dev -> dev.getTypes().equals(device.getTypes())))
.orElse(false);


https://habr.com/ru/post/346782/
