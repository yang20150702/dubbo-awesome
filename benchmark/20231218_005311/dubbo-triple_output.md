# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ops/ms
# Warmup Iteration   2: 12.104 ops/ms
# Warmup Iteration   3: 12.310 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.606 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.566 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (12.493, 12.566, 12.606), stdev = 0.064
  CI (99.9%): [11.406, 13.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.268 ops/ms
# Warmup Iteration   2: 13.004 ops/ms
# Warmup Iteration   3: 12.559 ops/ms
Iteration   1: 12.992 ops/ms
Iteration   2: 13.135 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.075 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (12.992, 13.075, 13.135), stdev = 0.074
  CI (99.9%): [11.725, 14.425] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.999 ops/ms
# Warmup Iteration   2: 12.457 ops/ms
# Warmup Iteration   3: 12.580 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.502 ops/ms
Iteration   3: 12.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.597 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (12.502, 12.597, 12.714), stdev = 0.107
  CI (99.9%): [10.637, 14.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.560 ops/ms
# Warmup Iteration   2: 10.189 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.293 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.340 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (10.293, 10.340, 10.395), stdev = 0.051
  CI (99.9%): [9.401, 11.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.005 ms/op
Iteration   1: 2.623 ±(99.9%) 0.004 ms/op
Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
Iteration   3: 2.584 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.594 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.575, 2.594, 2.623), stdev = 0.025
  CI (99.9%): [2.134, 3.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.497 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.495, 2.497, 2.502), stdev = 0.004
  CI (99.9%): [2.424, 2.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.504, 2.514, 2.528), stdev = 0.013
  CI (99.9%): [2.284, 2.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.005 ms/op
Iteration   2: 3.074 ±(99.9%) 0.005 ms/op
Iteration   3: 3.087 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.086 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.074, 3.086, 3.097), stdev = 0.011
  CI (99.9%): [2.876, 3.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.335 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  12.100 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 11.943 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.254 ms/op
                 createUser·p0.9999: 12.059 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375925
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179733 
    [ 2.500,  5.000) = 195334 
    [ 5.000,  7.500) = 458 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.406 ms/op
     p(99.9900) =     14.352 ms/op
     p(99.9990) =     24.409 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  7.383 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  7.374 ms/op
                 existUser·p0.9999: 13.372 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  8.881 ms/op
                 existUser·p0.9999: 11.961 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390031
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 195526 
    [ 2.500,  3.750) = 190396 
    [ 3.750,  5.000) = 2990 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.732 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     13.774 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.595 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.493 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  6.063 ms/op
                 getUser·p0.9999: 14.097 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.555 ms/op
                 getUser·p0.9999: 14.723 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.658 ms/op
                 getUser·p0.90:   3.187 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369285
  mean =      2.597 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 175843 
    [ 2.500,  3.750) = 185074 
    [ 3.750,  5.000) = 6957 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.719 ms/op
     p(99.9900) =     14.131 ms/op
     p(99.9990) =     14.896 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.097 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.722 ms/op
                 listUser·p0.999:  8.992 ms/op
                 listUser·p0.9999: 10.419 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.759 ms/op
                 listUser·p0.9999: 11.995 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   3: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.358 ms/op
                 listUser·p0.9999: 11.417 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312343
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 81619 
    [ 2.500,  3.750) = 186746 
    [ 3.750,  5.000) = 35611 
    [ 5.000,  6.250) = 6768 
    [ 6.250,  7.500) = 773 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 331 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.350 ms/op
     p(99.9990) =     12.515 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.566 ± 1.160  ops/ms
ClientPb.existUser                       thrpt       3  13.075 ± 1.350  ops/ms
ClientPb.getUser                         thrpt       3  12.597 ± 1.960  ops/ms
ClientPb.listUser                        thrpt       3  10.340 ± 0.939  ops/ms
ClientPb.createUser                       avgt       3   2.594 ± 0.460   ms/op
ClientPb.existUser                        avgt       3   2.497 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   3.086 ± 0.210   ms/op
ClientPb.createUser                     sample  375925   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.406           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.805           ms/op
ClientPb.existUser                      sample  390031   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.986           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.732           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  369285   2.597 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.493           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.642           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.719           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.131           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.466           ms/op
ClientPb.listUser                       sample  312343   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
