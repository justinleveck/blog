---
title: Project Euler - Problem 7
date: 2013-06-25 18:06 +00:00
tags: project-euler
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sit amet lectus quis nisi tristique scelerisque in vitae ipsum. Proin mauris massa, imperdiet id mi nec, scelerisque tempor mi. Donec eget rhoncus orci, quis adipiscing sapien. Pellentesque et posuere elit. Phasellus imperdiet vestibulum pulvinar. Integer sollicitudin velit eget massa sagittis, vel auctor metus laoreet. Sed viverra nulla lacus, ac bibendum purus rutrum ut.

Maecenas porta elit eget dolor tempus placerat. Vestibulum pharetra metus eu mi dignissim consectetur. Morbi magna nulla, rutrum at feugiat ac, egestas eget leo. Morbi ullamcorper risus massa, at egestas urna consequat ut. Aliquam vestibulum est eros, sit amet pretium elit elementum eu. Pellentesque posuere purus eget nisi varius, et semper ligula semper. Phasellus lacus felis, ornare nec malesuada a, tristique a felis. Nam elementum augue quam, sit amet ultrices est commodo sit amet. Praesent eu enim at tortor suscipit porta. Cras dolor lacus, vulputate vel justo quis, ullamcorper mollis tellus. Curabitur pellentesque porttitor purus, vitae dignissim lectus gravida sit amet. Sed ultricies pharetra lacus ut pulvinar.

```ruby
def prime? number
    return false if number == 0 || number == 1
    integers = *(2..Math.sqrt(number).round)
    integers.each do |i|
      return false if number % i == 0
    end
    true
end
 
def findPrime order
    count = 0
    number = 0
    while count != order
        number += 1
        count += 1 if prime? number
    end
    puts "The #{order} prime is #{number}"
    number
end

 
findPrime 10001`
```

Nullam at iaculis metus. Ut nec mattis enim, et venenatis nisi. Pellentesque vitae sem malesuada, laoreet arcu ac, lobortis nisi. Integer nec feugiat metus. Aliquam erat volutpat. Phasellus ultricies vitae neque ac placerat. Curabitur lacinia tristique lectus, eget dignissim sapien blandit cursus. Nunc sit amet turpis eu urna gravida viverra eu vitae metus. Praesent in aliquam tortor. Nulla dapibus elit massa, eget faucibus erat ultrices quis.

Sed eu magna tempus, laoreet purus et, ultrices ante. Suspendisse semper, mauris ac feugiat molestie, nulla est sagittis orci, sed hendrerit felis metus quis nisi. Maecenas luctus semper malesuada. Nullam pharetra, orci ac porta consectetur, leo lectus venenatis est, sit amet scelerisque mauris ante nec nibh. Vivamus orci metus, rhoncus posuere laoreet quis, facilisis ac metus. Nullam neque arcu, aliquet vitae urna ac, facilisis viverra nibh. Vivamus gravida lorem eget lorem elementum gravida.

Nam fringilla metus in hendrerit commodo. Fusce semper, dui at vehicula tristique, quam enim venenatis dui, in placerat turpis neque eget tortor. Quisque ut eros feugiat, volutpat urna vitae, bibendum felis. Mauris pretium ultricies pharetra. Pellentesque non magna eget nibh rhoncus vestibulum ullamcorper quis velit. Duis accumsan, nunc vitae aliquam porttitor, augue tellus elementum odio, a eleifend libero purus eu lacus. Sed dapibus ante justo. Donec bibendum quis erat viverra lacinia. Mauris elementum tellus eget mi scelerisque molestie. Aenean fermentum malesuada nulla, nec fringilla est iaculis non.

Donec posuere tortor in enim dictum imperdiet. Vivamus a interdum lacus. Ut lacus nulla, sodales ut venenatis non, mattis nec magna. Nam pharetra feugiat ante ac tempor. Proin rhoncus venenatis nibh vel ultricies. Donec placerat mattis ligula sit amet venenatis. Praesent elit nunc, porta quis quam non, scelerisque viverra magna.

Cras ultricies eleifend metus, sit amet semper eros. Morbi in tortor sed purus cursus ultricies. Fusce enim quam, aliquet eu adipiscing quis, tristique sed lectus. Quisque non nisi aliquet, aliquet metus nec, fermentum enim. Aliquam massa odio, consectetur nec felis eu, mollis bibendum quam. Maecenas quis scelerisque ante. Ut diam eros, interdum nec imperdiet at, laoreet ac felis.

Duis eu nibh orci. Cras commodo sollicitudin felis eu placerat. Cras euismod sagittis tortor eget tristique. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nulla pretium massa ac velit rhoncus rhoncus vitae nec tellus. Curabitur venenatis urna vel convallis porta. Nulla euismod porttitor mi, ac imperdiet diam lobortis id. Quisque massa arcu, imperdiet eu facilisis nec, molestie at lorem. Etiam vitae sem molestie ligula fermentum tristique. Suspendisse dapibus rutrum nunc, nec euismod libero posuere eu. Maecenas a laoreet massa. Ut scelerisque dictum tellus, at facilisis elit pellentesque eget. Nullam accumsan lorem id gravida luctus. Aenean eu molestie arcu.

Vivamus eleifend, nulla vitae gravida hendrerit, ipsum velit egestas tortor, eu porta arcu dolor in eros. Vestibulum lobortis ligula non leo molestie lobortis. Nulla facilisi. Nullam imperdiet sit amet risus in adipiscing. Aliquam eu metus tincidunt erat imperdiet iaculis. Pellentesque venenatis lorem magna, sit amet posuere leo ornare eu. Nulla sagittis, ligula ut dictum eleifend, massa est consequat sem, id feugiat purus ante non mi. Vivamus sagittis odio convallis lacus interdum, quis hendrerit magna commodo. Aliquam ullamcorper, augue id tristique imperdiet, sem metus vulputate lorem, quis bibendum arcu ligula at lacus. Duis tincidunt sit amet turpis sit amet dignissim. Cras pellentesque odio at nunc posuere sollicitudin. Morbi congue urna at quam venenatis, nec interdum eros facilisis. Sed sed lacinia nisl, eu dignissim erat. Phasellus ut pellentesque orci. Maecenas malesuada iaculis libero, nec dapibus mauris vestibulum eget. Vestibulum sit amet orci non risus hendrerit blandit.