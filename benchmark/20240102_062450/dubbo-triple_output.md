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
# Warmup Iteration   1: 4.842 ops/ms
# Warmup Iteration   2: 12.269 ops/ms
# Warmup Iteration   3: 12.508 ops/ms
Iteration   1: 12.668 ops/ms
Iteration   2: 12.663 ops/ms
Iteration   3: 12.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.644 ±(99.9%) 0.674 ops/ms [Average]
  (min, avg, max) = (12.602, 12.644, 12.668), stdev = 0.037
  CI (99.9%): [11.971, 13.318] (assumes normal distribution)


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
# Warmup Iteration   1: 8.063 ops/ms
# Warmup Iteration   2: 13.099 ops/ms
# Warmup Iteration   3: 13.076 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.123 ops/ms
Iteration   3: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.095 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (13.066, 13.095, 13.123), stdev = 0.028
  CI (99.9%): [12.583, 13.607] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.965 ops/ms
# Warmup Iteration   2: 12.804 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 12.998 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.965 ±(99.9%) 0.670 ops/ms [Average]
  (min, avg, max) = (12.926, 12.965, 12.998), stdev = 0.037
  CI (99.9%): [12.295, 13.635] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.656 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.721 ±(99.9%) 0.374 ops/ms [Average]
  (min, avg, max) = (10.698, 10.721, 10.738), stdev = 0.021
  CI (99.9%): [10.347, 11.095] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.560 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.505, 2.529, 2.560), stdev = 0.028
  CI (99.9%): [2.017, 3.041] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.003 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.470, 2.473, 2.478), stdev = 0.004
  CI (99.9%): [2.402, 2.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.472, 2.479, 2.495), stdev = 0.013
  CI (99.9%): [2.240, 2.719] (assumes normal distribution)


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
Iteration   3: 2.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.971, 2.976, 2.986), stdev = 0.008
  CI (99.9%): [2.830, 3.123] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  11.615 ms/op
                 createUser·p0.9999: 14.069 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  9.293 ms/op
                 createUser·p0.9999: 11.473 ms/op
                 createUser·p1.00:   12.321 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  8.484 ms/op
                 createUser·p0.9999: 10.961 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381017
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186283 
    [ 2.500,  5.000) = 193986 
    [ 5.000,  7.500) = 355 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.532 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.273 ms/op
                 existUser·p0.999:  5.563 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  5.850 ms/op
                 existUser·p0.9999: 12.338 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.526 ms/op
                 existUser·p0.999:  7.687 ms/op
                 existUser·p0.9999: 12.174 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388932
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 192282 
    [ 2.500,  3.750) = 194361 
    [ 3.750,  5.000) = 1568 
    [ 5.000,  6.250) = 299 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =      6.573 ms/op
     p(99.9900) =     12.978 ms/op
     p(99.9990) =     13.309 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  5.892 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  8.867 ms/op
                 getUser·p0.9999: 19.503 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.034 ms/op
                 getUser·p0.999:  8.548 ms/op
                 getUser·p0.9999: 11.010 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387316
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195254 
    [ 2.500,  5.000) = 190681 
    [ 5.000,  7.500) = 927 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.451 ms/op
     p(99.9900) =     14.209 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.845 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.009 ms/op
Iteration   1: 2.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.050 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   10.945 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 12.077 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 13.321 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323643
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 100751 
    [ 2.500,  3.750) = 187870 
    [ 3.750,  5.000) = 28432 
    [ 5.000,  6.250) = 5104 
    [ 6.250,  7.500) = 656 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     12.495 ms/op
     p(99.9990) =     13.998 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.644 ± 0.674  ops/ms
ClientPb.existUser                       thrpt       3  13.095 ± 0.512  ops/ms
ClientPb.getUser                         thrpt       3  12.965 ± 0.670  ops/ms
ClientPb.listUser                        thrpt       3  10.721 ± 0.374  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.512   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.240   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.147   ms/op
ClientPb.createUser                     sample  381017   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.944           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.725           ms/op
ClientPb.existUser                      sample  388932   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.027           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.573           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.978           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.697           ms/op
ClientPb.getUser                        sample  387316   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.807           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.709           ms/op
ClientPb.listUser                       sample  323643   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.495           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
