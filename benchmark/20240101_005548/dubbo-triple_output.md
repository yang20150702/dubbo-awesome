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
# Warmup Iteration   1: 4.693 ops/ms
# Warmup Iteration   2: 11.889 ops/ms
# Warmup Iteration   3: 12.293 ops/ms
Iteration   1: 12.467 ops/ms
Iteration   2: 12.538 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.552 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (12.467, 12.552, 12.653), stdev = 0.094
  CI (99.9%): [10.838, 14.267] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.443 ops/ms
# Warmup Iteration   2: 13.005 ops/ms
# Warmup Iteration   3: 12.897 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.925 ops/ms
Iteration   3: 13.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.924 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (12.777, 12.924, 13.070), stdev = 0.146
  CI (99.9%): [10.256, 15.592] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 12.626 ops/ms
# Warmup Iteration   3: 12.661 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.866 ops/ms
Iteration   3: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.801 ±(99.9%) 2.954 ops/ms [Average]
  (min, avg, max) = (12.616, 12.801, 12.919), stdev = 0.162
  CI (99.9%): [9.847, 15.754] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.554 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.602 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (10.579, 10.602, 10.624), stdev = 0.023
  CI (99.9%): [10.187, 11.017] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.539, 2.554, 2.572), stdev = 0.017
  CI (99.9%): [2.246, 2.861] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.464, 2.476, 2.487), stdev = 0.011
  CI (99.9%): [2.268, 2.683] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
Iteration   3: 2.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.506, 2.521, 2.533), stdev = 0.014
  CI (99.9%): [2.267, 2.776] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.004 ms/op
Iteration   1: 3.000 ±(99.9%) 0.007 ms/op
Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
Iteration   3: 2.977 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.984 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.975, 2.984, 3.000), stdev = 0.014
  CI (99.9%): [2.733, 3.234] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.527 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.640 ms/op
                 createUser·p0.9999: 14.220 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.456 ms/op
                 createUser·p0.9999: 12.342 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.990 ms/op
                 createUser·p0.9999: 13.221 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377377
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 181263 
    [ 2.500,  3.750) = 191963 
    [ 3.750,  5.000) = 3303 
    [ 5.000,  6.250) = 346 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.535 ms/op
     p(99.9990) =     15.644 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  11.244 ms/op
                 existUser·p0.9999: 16.664 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  5.998 ms/op
                 existUser·p0.9999: 11.238 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389898
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 195587 
    [ 2.500,  3.750) = 190728 
    [ 3.750,  5.000) = 2759 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.769 ms/op
     p(99.9900) =     15.418 ms/op
     p(99.9990) =     16.879 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  11.753 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.535 ms/op
                 getUser·p0.999:  10.191 ms/op
                 getUser·p0.9999: 13.420 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.648 ms/op
                 getUser·p0.9999: 11.158 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376389
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 183238 
    [ 2.500,  3.750) = 187320 
    [ 3.750,  5.000) = 4626 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     13.441 ms/op
     p(99.9990) =     14.318 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.286 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318263
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 91790 
    [ 2.500,  3.750) = 187488 
    [ 3.750,  5.000) = 31667 
    [ 5.000,  6.250) = 5810 
    [ 6.250,  7.500) = 674 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.114 ms/op
     p(99.9990) =     11.548 ms/op
     p(99.9999) =     11.616 ms/op
    p(100.0000) =     11.616 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.552 ± 1.714  ops/ms
ClientPb.existUser                       thrpt       3  12.924 ± 2.668  ops/ms
ClientPb.getUser                         thrpt       3  12.801 ± 2.954  ops/ms
ClientPb.listUser                        thrpt       3  10.602 ± 0.415  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.308   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.208   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.254   ms/op
ClientPb.listUser                         avgt       3   2.984 ± 0.250   ms/op
ClientPb.createUser                     sample  377377   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.535           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.630           ms/op
ClientPb.existUser                      sample  389898   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.769           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.974           ms/op
ClientPb.getUser                        sample  376389   2.548 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.857           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.441           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  318263   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.114           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.616           ms/op
