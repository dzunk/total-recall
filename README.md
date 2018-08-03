# Total Recall

A deep dive into Ruby memory management. I originally gave this talk in July 2018 at a [meetup](https://www.meetup.com/weedmaps-engineering/events/252718657/) hosted by [Weedmaps](https://weedmaps.com).

## References

### Posts

I am incredibly grateful to the giants whose shoulders I stood on in order to put this talk together. Presented in alphabetical order.
* [Debugging Memory Leaks in Ruby](https://samsaffron.com/archive/2015/03/31/debugging-memory-leaks-in-ruby) by [Sam Saffron](https://twitter.com/samsaffron)
* [Demystifying the Ruby GC](https://samsaffron.com/archive/2013/11/22/demystifying-the-ruby-gc) by [Sam Saffron](https://twitter.com/samsaffron)
* [How I spent two weeks hunting a memory leak in Ruby](http://www.be9.io/2015/09/21/memory-leak/) by [Oleg Dashevskii](http://www.be9.io/about/)
* [How Ruby Uses Memory](https://www.sitepoint.com/ruby-uses-memory/) by [Richard Schneeman](https://twitter.com/schneems)
* [Hunting Down Memory Issues In Ruby: A Definitive Guide](https://www.toptal.com/ruby/hunting-ruby-memory-issues) by [Bruz Marzolf](https://twitter.com/bruzilla)
* [Incremental Garbage Collection in Ruby 2.2](https://blog.heroku.com/incremental-gc) by [Koichi Sasada](http://www.atdot.net/~ko1/)
* [Mark and Sweep Garbage Collection Algorithm](https://www.geeksforgeeks.org/mark-and-sweep-garbage-collection-algorithm/) by [Chirag Agarwal](https://github.com/chiragragarwal)
* [Optimizing Rails for Memory Usage](https://collectiveidea.com/blog/archives/2015/02/19/optimizing-rails-for-memory-usage-part-2-tuning-the-gc) by [Brian Hempel](https://twitter.com/brianhempel)
* [Ruby Memory Environment Variables - Simpler Than They Look](http://engineering.appfolio.com/appfolio-engineering/2018/6/27/ruby-memory-environment-variables-simpler-than-they-look) by [Noah Gibbs](https://twitter.com/codefolio)
* [Ruby Hacking Guide: Garbage Collection](https://ruby-hacking-guide.github.io/gc.html) by [Minero Aoki](https://github.com/aamine)
* [Using lazy enumerators to work with large files in Ruby](http://blog.honeybadger.io/using-lazy-enumerators-to-work-with-large-files-in-ruby/) by [Starr Horne](https://twitter.com/StarrHorne)
* [Visualizing Your Ruby Heap](https://tenderlovemaking.com/2017/09/27/visualizing-your-ruby-heap.html) by [Aaron Patterson](https://twitter.com/tenderlove)

### Videos
* [RubyConf 2017: Building a Compacting GC for MRI](https://www.youtube.com/watch?v=8Q7M513vewk) by [Aaron Patterson](https://twitter.com/tenderlove)

### Documentation

Some of the relevant Ruby standard library modules.
* [Enumerator::Lazy](http://ruby-doc.org/core-2.5.1/Enumerator/Lazy.html)
* [GC](https://ruby-doc.org/core-2.5.1/GC.html)
* [ObjectSpace](https://ruby-doc.org/core-2.5.1/ObjectSpace.html)

## Tools

### APM

* [New Relic](https://newrelic.com/)
* [Skylight](https://www.skylight.io/)
* [Scout](https://scoutapp.com/)

### Gems

* [allocation_stats](https://github.com/srawlins/allocation_stats)
* [derailed_benchmarks](https://github.com/schneems/derailed_benchmarks)
* [gc_tracer](https://github.com/ko1/gc_tracer)
* [heapfrag](https://github.com/tenderlove/heapfrag)
* [memory_profiler](https://github.com/SamSaffron/memory_profiler)
* [rbtrace](https://github.com/tmm1/rbtrace)
