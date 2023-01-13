# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.041 ops/ms
# Warmup Iteration   2: 5.992 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 8.992 ops/ms
Iteration   2: 9.315 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.281 ±(99.9%) 4.989 ops/ms [Average]
  (min, avg, max) = (8.992, 9.281, 9.536), stdev = 0.273
  CI (99.9%): [4.292, 14.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 9.045 ops/ms
Iteration   1: 9.252 ops/ms
Iteration   2: 9.502 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.483 ±(99.9%) 4.039 ops/ms [Average]
  (min, avg, max) = (9.252, 9.483, 9.694), stdev = 0.221
  CI (99.9%): [5.444, 13.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.902 ops/ms
# Warmup Iteration   2: 7.779 ops/ms
# Warmup Iteration   3: 9.267 ops/ms
Iteration   1: 9.263 ops/ms
Iteration   2: 9.231 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.327 ±(99.9%) 2.553 ops/ms [Average]
  (min, avg, max) = (9.231, 9.327, 9.488), stdev = 0.140
  CI (99.9%): [6.774, 11.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 7.100 ops/ms
# Warmup Iteration   3: 7.868 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.069 ±(99.9%) 4.546 ops/ms [Average]
  (min, avg, max) = (7.784, 8.069, 8.247), stdev = 0.249
  CI (99.9%): [3.523, 12.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.633 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.005 ms/op
Iteration   1: 3.436 ±(99.9%) 0.006 ms/op
Iteration   2: 3.515 ±(99.9%) 0.004 ms/op
Iteration   3: 3.330 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.427 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (3.330, 3.427, 3.515), stdev = 0.093
  CI (99.9%): [1.730, 5.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.146 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.340 ±(99.9%) 0.007 ms/op
Iteration   2: 3.280 ±(99.9%) 0.004 ms/op
Iteration   3: 3.276 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.276, 3.299, 3.340), stdev = 0.036
  CI (99.9%): [2.642, 3.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.603 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.007 ms/op
Iteration   1: 3.516 ±(99.9%) 0.005 ms/op
Iteration   2: 3.454 ±(99.9%) 0.007 ms/op
Iteration   3: 3.335 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.435 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (3.335, 3.435, 3.516), stdev = 0.092
  CI (99.9%): [1.752, 5.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.397 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.008 ms/op
Iteration   1: 4.143 ±(99.9%) 0.013 ms/op
Iteration   2: 4.115 ±(99.9%) 0.005 ms/op
Iteration   3: 4.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.089 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (4.011, 4.089, 4.143), stdev = 0.070
  CI (99.9%): [2.817, 5.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.951 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.010 ms/op
Iteration   1: 3.596 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  11.815 ms/op
                 createUser·p0.9999: 22.584 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.500 ms/op
                 createUser·p0.999:  23.132 ms/op
                 createUser·p0.9999: 27.256 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.615 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 27.137 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269442
  mean =      3.562 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12285 
    [ 2.500,  5.000) = 249956 
    [ 5.000,  7.500) = 6017 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     16.912 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.494 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
Iteration   1: 3.368 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 23.216 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.077 ms/op
                 existUser·p0.999:  23.048 ms/op
                 existUser·p0.9999: 28.992 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  20.842 ms/op
                 existUser·p0.9999: 25.416 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280907
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11309 
    [ 2.500,  5.000) = 263104 
    [ 5.000,  7.500) = 5551 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.177 ms/op
     p(99.9900) =     27.290 ms/op
     p(99.9990) =     29.182 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.282 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.012 ms/op
Iteration   1: 3.685 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  15.850 ms/op
                 getUser·p0.9999: 22.555 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   2: 3.471 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  20.382 ms/op
                 getUser·p0.9999: 22.931 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.310 ms/op
                 getUser·p0.999:  19.464 ms/op
                 getUser·p0.9999: 24.392 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271562
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3212 
    [ 2.500,  5.000) = 259391 
    [ 5.000,  7.500) = 6968 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     23.583 ms/op
     p(99.9990) =     25.928 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.662 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.598 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   2: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.041 ms/op
                 listUser·p0.9999: 18.586 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.104 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.750 ms/op
                 listUser·p0.9999: 17.112 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235803
  mean =      4.070 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 223984 
    [ 5.000,  7.500) = 9824 
    [ 7.500, 10.000) = 1194 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     28.708 ms/op
     p(99.9990) =     30.746 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.281 ± 4.989  ops/ms
ClientPb.existUser                       thrpt       3   9.483 ± 4.039  ops/ms
ClientPb.getUser                         thrpt       3   9.327 ± 2.553  ops/ms
ClientPb.listUser                        thrpt       3   8.069 ± 4.546  ops/ms
ClientPb.createUser                       avgt       3   3.427 ± 1.697   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.656   ms/op
ClientPb.getUser                          avgt       3   3.435 ± 1.683   ms/op
ClientPb.listUser                         avgt       3   4.089 ± 1.272   ms/op
ClientPb.createUser                     sample  269442   3.562 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.021           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.912           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  280907   3.417 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.177           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.290           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  271562   3.532 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.389           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.583           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  235803   4.070 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.985           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.708           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.867           ms/op
