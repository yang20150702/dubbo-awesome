# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.443 ops/ms
# Warmup Iteration   2: 5.986 ops/ms
# Warmup Iteration   3: 8.939 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 9.828 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.865 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (9.820, 9.865, 9.948), stdev = 0.072
  CI (99.9%): [8.554, 11.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 8.714 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.394 ±(99.9%) 3.117 ops/ms [Average]
  (min, avg, max) = (10.291, 10.394, 10.591), stdev = 0.171
  CI (99.9%): [7.277, 13.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 9.246 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 10.050 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 9.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.030 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (9.939, 10.030, 10.101), stdev = 0.083
  CI (99.9%): [8.520, 11.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 8.547 ops/ms
Iteration   1: 8.471 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 8.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.462 ±(99.9%) 3.153 ops/ms [Average]
  (min, avg, max) = (8.284, 8.462, 8.630), stdev = 0.173
  CI (99.9%): [5.309, 11.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.416 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
Iteration   3: 3.297 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.212 ±(99.9%) 2.035 ms/op [Average]
  (min, avg, max) = (3.086, 3.212, 3.297), stdev = 0.112
  CI (99.9%): [1.178, 5.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.743 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.004 ms/op
Iteration   1: 3.150 ±(99.9%) 0.003 ms/op
Iteration   2: 3.335 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.169 ±(99.9%) 2.854 ms/op [Average]
  (min, avg, max) = (3.024, 3.169, 3.335), stdev = 0.156
  CI (99.9%): [0.315, 6.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.756 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.004 ms/op
Iteration   1: 3.272 ±(99.9%) 0.004 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.170 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.119, 3.170, 3.272), stdev = 0.088
  CI (99.9%): [1.560, 4.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.925 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
Iteration   1: 3.772 ±(99.9%) 0.007 ms/op
Iteration   2: 3.908 ±(99.9%) 0.004 ms/op
Iteration   3: 3.810 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.830 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.772, 3.830, 3.908), stdev = 0.070
  CI (99.9%): [2.552, 5.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.147 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  18.175 ms/op
                 createUser·p0.9999: 22.567 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 3.396 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  18.933 ms/op
                 createUser·p0.9999: 35.962 ms/op
                 createUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288603
  mean =      3.324 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18826 
    [ 2.500,  5.000) = 262009 
    [ 5.000,  7.500) = 6598 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.217 ms/op
     p(99.9000) =     18.494 ms/op
     p(99.9900) =     32.904 ms/op
     p(99.9990) =     37.181 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.477 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  10.569 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 23.090 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.790 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301238
  mean =      3.184 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25779 
    [ 2.500,  5.000) = 269798 
    [ 5.000,  7.500) = 4845 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.464 ms/op
     p(99.9900) =     23.818 ms/op
     p(99.9990) =     25.001 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.010 ms/op
Iteration   1: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 23.530 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.037 ms/op
                 getUser·p0.90:   3.360 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  12.609 ms/op
                 getUser·p0.9999: 28.834 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302890
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14392 
    [ 2.500,  5.000) = 282861 
    [ 5.000,  7.500) = 4998 
    [ 7.500, 10.000) = 249 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.257 ms/op
     p(99.9900) =     27.932 ms/op
     p(99.9990) =     29.457 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.351 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 30.712 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 3.770 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.762 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 16.507 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252766
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 243369 
    [ 5.000,  7.500) = 7119 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     27.793 ms/op
     p(99.9990) =     31.193 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.865 ± 1.311  ops/ms
ClientPb.existUser                       thrpt       3  10.394 ± 3.117  ops/ms
ClientPb.getUser                         thrpt       3  10.030 ± 1.510  ops/ms
ClientPb.listUser                        thrpt       3   8.462 ± 3.153  ops/ms
ClientPb.createUser                       avgt       3   3.212 ± 2.035   ms/op
ClientPb.existUser                        avgt       3   3.169 ± 2.854   ms/op
ClientPb.getUser                          avgt       3   3.170 ± 1.611   ms/op
ClientPb.listUser                         avgt       3   3.830 ± 1.279   ms/op
ClientPb.createUser                     sample  288603   3.324 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.904           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.487           ms/op
ClientPb.existUser                      sample  301238   3.184 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.464           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  302890   3.165 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.219           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.456           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.257           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  252766   3.797 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.763           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.793           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.392           ms/op
