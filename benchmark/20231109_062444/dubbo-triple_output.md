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
# Warmup Iteration   1: 4.908 ops/ms
# Warmup Iteration   2: 12.456 ops/ms
# Warmup Iteration   3: 12.495 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.878 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.793 ±(99.9%) 2.220 ops/ms [Average]
  (min, avg, max) = (12.653, 12.793, 12.878), stdev = 0.122
  CI (99.9%): [10.572, 15.013] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.605 ops/ms
# Warmup Iteration   2: 12.931 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.266 ops/ms
Iteration   2: 13.196 ops/ms
Iteration   3: 13.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.259 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (13.196, 13.259, 13.314), stdev = 0.059
  CI (99.9%): [12.177, 14.341] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.737 ops/ms
# Warmup Iteration   2: 12.717 ops/ms
# Warmup Iteration   3: 12.803 ops/ms
Iteration   1: 12.897 ops/ms
Iteration   2: 12.875 ops/ms
Iteration   3: 12.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.826 ±(99.9%) 1.919 ops/ms [Average]
  (min, avg, max) = (12.705, 12.826, 12.897), stdev = 0.105
  CI (99.9%): [10.906, 14.745] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.644 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.608 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (10.460, 10.608, 10.714), stdev = 0.132
  CI (99.9%): [8.204, 13.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.003 ms/op
Iteration   1: 2.520 ±(99.9%) 0.003 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.517, 2.521, 2.525), stdev = 0.004
  CI (99.9%): [2.447, 2.594] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.603 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.453 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.452, 2.454, 2.457), stdev = 0.002
  CI (99.9%): [2.411, 2.497] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.003 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.486, 2.503, 2.523), stdev = 0.018
  CI (99.9%): [2.166, 2.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.064 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (3.043, 3.064, 3.085), stdev = 0.021
  CI (99.9%): [2.686, 3.442] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  12.335 ms/op
                 createUser·p0.9999: 14.226 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.018 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 11.911 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.005 ms/op
                 createUser·p0.9999: 11.805 ms/op
                 createUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378169
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 181715 
    [ 2.500,  3.750) = 191559 
    [ 3.750,  5.000) = 3823 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.839 ms/op
     p(99.9900) =     13.736 ms/op
     p(99.9990) =     14.438 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.678 ms/op
                 existUser·p0.9999: 14.186 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.014 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  6.069 ms/op
                 existUser·p0.9999: 12.450 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394689
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 196061 
    [ 2.500,  3.750) = 195293 
    [ 3.750,  5.000) = 2696 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      5.669 ms/op
     p(99.9900) =     13.296 ms/op
     p(99.9990) =     15.323 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.887 ms/op
                 getUser·p0.9999: 12.097 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  7.359 ms/op
                 getUser·p0.9999: 11.438 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381188
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 186317 
    [ 2.500,  3.750) = 188807 
    [ 3.750,  5.000) = 4800 
    [ 5.000,  6.250) = 762 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      8.893 ms/op
     p(99.9900) =     14.590 ms/op
     p(99.9990) =     15.138 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.009 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.188 ms/op
                 listUser·p1.00:   12.796 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 15.684 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.245 ms/op
                 listUser·p0.9999: 11.998 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316963
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 89684 
    [ 2.500,  3.750) = 186396 
    [ 3.750,  5.000) = 33118 
    [ 5.000,  6.250) = 6166 
    [ 6.250,  7.500) = 707 
    [ 7.500,  8.750) = 360 
    [ 8.750, 10.000) = 184 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.206 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.793 ± 2.220  ops/ms
ClientPb.existUser                       thrpt       3  13.259 ± 1.082  ops/ms
ClientPb.getUser                         thrpt       3  12.826 ± 1.919  ops/ms
ClientPb.listUser                        thrpt       3  10.608 ± 2.403  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.074   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.043   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.337   ms/op
ClientPb.listUser                         avgt       3   3.064 ± 0.378   ms/op
ClientPb.createUser                     sample  378169   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  394689   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.764           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.669           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.296           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.138           ms/op
ClientPb.getUser                        sample  381188   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.893           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.590           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  316963   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.466           ms/op
