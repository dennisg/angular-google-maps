angular-google-maps
===================

AngularJS directives for the Google Maps Javascript API


added a map-type-id attribute to allow for changing the mapTypeId

        <div class="google-map" 
            center="centerProperty"
            map-type-id="typeProperty"
            zoom="zoomProperty" 
            markers="markersProperty"
            mark-click="false"
            draggable="true"
            fit="true"
            style="height: 400px; width: 100%">
        </div>

scope:

    angular.extend($scope, {
    ...
        typeProperty : google.maps.MapTypeId.TERRAIN,
    ...
    });