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
# Warmup Iteration   1: 4.837 ops/ms
# Warmup Iteration   2: 12.188 ops/ms
# Warmup Iteration   3: 12.558 ops/ms
Iteration   1: 12.650 ops/ms
Iteration   2: 12.891 ops/ms
Iteration   3: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.810 ±(99.9%) 2.519 ops/ms [Average]
  (min, avg, max) = (12.650, 12.810, 12.891), stdev = 0.138
  CI (99.9%): [10.290, 15.329] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ops/ms
# Warmup Iteration   2: 13.336 ops/ms
# Warmup Iteration   3: 13.184 ops/ms
Iteration   1: 13.187 ops/ms
Iteration   2: 13.287 ops/ms
Iteration   3: 13.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.268 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (13.187, 13.268, 13.330), stdev = 0.074
  CI (99.9%): [11.926, 14.610] (assumes normal distribution)


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
# Warmup Iteration   1: 7.778 ops/ms
# Warmup Iteration   2: 12.736 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 12.737 ops/ms
Iteration   3: 12.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.843 ±(99.9%) 2.882 ops/ms [Average]
  (min, avg, max) = (12.737, 12.843, 13.025), stdev = 0.158
  CI (99.9%): [9.961, 15.725] (assumes normal distribution)


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
# Warmup Iteration   1: 6.732 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.677 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (10.634, 10.677, 10.751), stdev = 0.065
  CI (99.9%): [9.500, 11.854] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
Iteration   3: 2.531 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.523, 2.537, 2.556), stdev = 0.017
  CI (99.9%): [2.226, 2.848] (assumes normal distribution)


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.420, 2.436, 2.447), stdev = 0.014
  CI (99.9%): [2.183, 2.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.003 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.472 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.472, 2.479, 2.482), stdev = 0.005
  CI (99.9%): [2.379, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.004 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
Iteration   3: 2.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.965, 2.968, 2.972), stdev = 0.004
  CI (99.9%): [2.904, 3.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.672 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.911 ms/op
                 createUser·p0.9999: 13.549 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.496 ms/op
                 createUser·p0.9999: 12.283 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.888 ms/op
                 createUser·p0.999:  9.862 ms/op
                 createUser·p0.9999: 11.377 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382170
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 184942 
    [ 2.500,  3.750) = 193425 
    [ 3.750,  5.000) = 2908 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.713 ms/op
     p(99.9900) =     13.153 ms/op
     p(99.9990) =     13.820 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.220 ms/op
                 existUser·p0.9999: 13.677 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 12.888 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  8.154 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394629
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 195199 
    [ 2.500,  3.750) = 196785 
    [ 3.750,  5.000) = 1923 
    [ 5.000,  6.250) = 238 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      7.187 ms/op
     p(99.9900) =     13.313 ms/op
     p(99.9990) =     14.091 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  11.875 ms/op
                 getUser·p0.9999: 13.791 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.706 ms/op
                 getUser·p0.9999: 16.926 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.563 ms/op
                 getUser·p0.999:  8.179 ms/op
                 getUser·p0.9999: 12.230 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376484
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183398 
    [ 2.500,  3.750) = 188304 
    [ 3.750,  5.000) = 3522 
    [ 5.000,  6.250) = 769 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.755 ms/op
     p(99.9900) =     14.489 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.528 ms/op
                 listUser·p0.9999: 13.213 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.158 ms/op
                 listUser·p0.9999: 10.436 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.352 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.037 ms/op
                 listUser·p0.9999: 10.113 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323137
  mean =      2.968 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 99896 
    [ 2.500,  3.750) = 185825 
    [ 3.750,  5.000) = 30440 
    [ 5.000,  6.250) = 5521 
    [ 6.250,  7.500) = 620 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     12.278 ms/op
     p(99.9990) =     13.387 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.810 ± 2.519  ops/ms
ClientPb.existUser                       thrpt       3  13.268 ± 1.342  ops/ms
ClientPb.getUser                         thrpt       3  12.843 ± 2.882  ops/ms
ClientPb.listUser                        thrpt       3  10.677 ± 1.177  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.252   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.100   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.065   ms/op
ClientPb.createUser                     sample  382170   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.153           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  394629   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.771           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.187           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  376484   2.548 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.951           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.755           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.489           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  323137   2.968 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.883           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.278           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
