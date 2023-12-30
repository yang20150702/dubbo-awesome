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
# Warmup Iteration   1: 5.424 ops/ms
# Warmup Iteration   2: 12.097 ops/ms
# Warmup Iteration   3: 12.103 ops/ms
Iteration   1: 12.510 ops/ms
Iteration   2: 12.363 ops/ms
Iteration   3: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.460 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (12.363, 12.460, 12.510), stdev = 0.085
  CI (99.9%): [10.914, 14.007] (assumes normal distribution)


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
# Warmup Iteration   1: 8.495 ops/ms
# Warmup Iteration   2: 13.021 ops/ms
# Warmup Iteration   3: 13.028 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 12.997 ops/ms
Iteration   3: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.972 ±(99.9%) 0.437 ops/ms [Average]
  (min, avg, max) = (12.950, 12.972, 12.997), stdev = 0.024
  CI (99.9%): [12.535, 13.408] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ops/ms
# Warmup Iteration   2: 12.381 ops/ms
# Warmup Iteration   3: 12.786 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.695 ±(99.9%) 0.797 ops/ms [Average]
  (min, avg, max) = (12.645, 12.695, 12.724), stdev = 0.044
  CI (99.9%): [11.898, 13.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.863 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.620 ±(99.9%) 0.110 ops/ms [Average]
  (min, avg, max) = (10.614, 10.620, 10.626), stdev = 0.006
  CI (99.9%): [10.510, 10.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.003 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (2.544, 2.571, 2.603), stdev = 0.030
  CI (99.9%): [2.029, 3.113] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.464, 2.480, 2.489), stdev = 0.014
  CI (99.9%): [2.233, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.506, 2.515, 2.531), stdev = 0.014
  CI (99.9%): [2.269, 2.762] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.000, 3.003, 3.009), stdev = 0.005
  CI (99.9%): [2.904, 3.102] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
Iteration   1: 2.568 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.772 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 14.319 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  5.599 ms/op
                 createUser·p0.9999: 27.889 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374145
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179221 
    [ 2.500,  5.000) = 194356 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.484 ms/op
     p(99.9900) =     14.411 ms/op
     p(99.9990) =     28.173 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  11.569 ms/op
                 existUser·p0.9999: 13.520 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.701 ms/op
                 existUser·p0.9999: 13.169 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  9.640 ms/op
                 existUser·p0.9999: 15.532 ms/op
                 existUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382640
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 187128 
    [ 2.500,  3.750) = 192337 
    [ 3.750,  5.000) = 2461 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      8.417 ms/op
     p(99.9900) =     13.639 ms/op
     p(99.9990) =     15.715 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.453 ms/op
                 getUser·p0.9999: 14.472 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.623 ms/op
                 getUser·p0.999:  9.131 ms/op
                 getUser·p0.9999: 14.404 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 11.475 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376570
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 182941 
    [ 2.500,  3.750) = 188223 
    [ 3.750,  5.000) = 4233 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.981 ms/op
     p(99.9900) =     14.070 ms/op
     p(99.9990) =     14.675 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.520 ms/op
                 listUser·p0.9999: 11.002 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.451 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.870 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315594
  mean =      3.039 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 85612 
    [ 2.500,  3.750) = 190089 
    [ 3.750,  5.000) = 32898 
    [ 5.000,  6.250) = 5735 
    [ 6.250,  7.500) = 456 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.558 ms/op
     p(99.9990) =     12.004 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.460 ± 1.546  ops/ms
ClientPb.existUser                       thrpt       3  12.972 ± 0.437  ops/ms
ClientPb.getUser                         thrpt       3  12.695 ± 0.797  ops/ms
ClientPb.listUser                        thrpt       3  10.620 ± 0.110  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.542   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.247   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.247   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.099   ms/op
ClientPb.createUser                     sample  374145   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.856           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.484           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  382640   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.417           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.639           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.778           ms/op
ClientPb.getUser                        sample  376570   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.981           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  315594   3.039 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.558           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.157           ms/op
