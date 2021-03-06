# Geo::Coder::List

Provide lots of backends for HTML::GoogleMaps::V3

# VERSION

Version 0.01

# SYNOPSIS

[Geo::Coder::All](https://metacpan.org/pod/Geo::Coder::All) and [Geo::Coder::Many](https://metacpan.org/pod/Geo::Coder::Many) are great routines but neither quite does what I want.
This module's primary use is to all many backends to be used by [HTML::GoogleMaps::V3](https://metacpan.org/pod/HTML::GoogleMaps::V3)

# SUBROUTINES/METHODS

## new

Creates a Geo::Coder::List object.

## push

Add an encoder to list of encoders.

        use Geo::Coder::List;
        use Geo::Coder::GooglePlaces;

        my $list = Geo::Coder::List->new()->push(Geo::Coder::GooglePlaces->new());

## geocode

Runs geocode on all of the loaded drivers.
See [Geo::Coder::GooglePlaces::V3](https://metacpan.org/pod/Geo::Coder::GooglePlaces::V3) for an explanation

# AUTHOR

Nigel Horne, `<njh at bandsman.co.uk>`

# BUGS

Please report any bugs or feature requests to `bug-geo-coder-list at rt.cpan.org`,
or through the web interface at
[http://rt.cpan.org/NoAuth/ReportBug.html?Queue=Geo-Coder-List](http://rt.cpan.org/NoAuth/ReportBug.html?Queue=Geo-Coder-List).
I will be notified, and then you'll
automatically be notified of progress on your bug as I make changes.

# SEE ALSO

[Geo::Coder::Many](https://metacpan.org/pod/Geo::Coder::Many)
[Geo::Coder::All](https://metacpan.org/pod/Geo::Coder::All)
[Geo::Coder::GooglePlaces](https://metacpan.org/pod/Geo::Coder::GooglePlaces)

# SUPPORT

You can find documentation for this module with the perldoc command.

    perldoc Geo::Coder::List

You can also look for information at:

- RT: CPAN's request tracker

    [http://rt.cpan.org/NoAuth/Bugs.html?Dist=Geo-Coder-List](http://rt.cpan.org/NoAuth/Bugs.html?Dist=Geo-Coder-List)

- AnnoCPAN: Annotated CPAN documentation

    [http://annocpan.org/dist/Geo-Coder-List](http://annocpan.org/dist/Geo-Coder-List)

- CPAN Ratings

    [http://cpanratings.perl.org/d/Geo-Coder-List](http://cpanratings.perl.org/d/Geo-Coder-List)

- Search CPAN

    [http://search.cpan.org/dist/Geo-Coder-List/](http://search.cpan.org/dist/Geo-Coder-List/)

# LICENSE AND COPYRIGHT

Copyright 2016 Nigel Horne.

This program is released under the following licence: GPL
