# SimpleAngularSwiper

simple implementation of https://github.com/nolimits4web/Swiper for angularJS


## Installation

```
bower install simple-angular-swiper
```

## Usage

```html
<div
        class="swiper-container"
        data-autoplay="0"
        data-loop="1"
        data-slides-per-view="3"
        data-breakpoints='{"300": {"slidesPerView":1},"500": {"slidesPerView":2}}'
>
    <div class="swiper-wrapper">
        <div class="swiper-slide" ng-repeat="data in someList">
            <div class="paddings-container">
                <ng-include src="'slide.html'"></ng-include>
            </div>
        </div>
    </div>
    <div class="pagination"></div>
</div>
```

