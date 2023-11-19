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
# Warmup Iteration   1: 4.881 ops/ms
# Warmup Iteration   2: 11.953 ops/ms
# Warmup Iteration   3: 12.381 ops/ms
Iteration   1: 12.556 ops/ms
Iteration   2: 12.683 ops/ms
Iteration   3: 12.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.684 ±(99.9%) 2.344 ops/ms [Average]
  (min, avg, max) = (12.556, 12.684, 12.813), stdev = 0.128
  CI (99.9%): [10.340, 15.028] (assumes normal distribution)


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
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 12.788 ops/ms
# Warmup Iteration   3: 12.898 ops/ms
Iteration   1: 12.869 ops/ms
Iteration   2: 13.065 ops/ms
Iteration   3: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.967 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (12.869, 12.967, 13.065), stdev = 0.098
  CI (99.9%): [11.182, 14.751] (assumes normal distribution)


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
# Warmup Iteration   1: 7.263 ops/ms
# Warmup Iteration   2: 12.488 ops/ms
# Warmup Iteration   3: 12.640 ops/ms
Iteration   1: 12.613 ops/ms
Iteration   2: 12.673 ops/ms
Iteration   3: 12.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.674 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (12.613, 12.674, 12.735), stdev = 0.061
  CI (99.9%): [11.560, 13.787] (assumes normal distribution)


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
# Warmup Iteration   1: 6.891 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.475 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.600 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.611 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.575, 10.611, 10.658), stdev = 0.042
  CI (99.9%): [9.837, 11.385] (assumes normal distribution)


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
Iteration   1: 2.605 ±(99.9%) 0.004 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.575 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.591 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.575, 2.591, 2.605), stdev = 0.015
  CI (99.9%): [2.310, 2.871] (assumes normal distribution)


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.476, 2.480, 2.487), stdev = 0.006
  CI (99.9%): [2.369, 2.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.003 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.559 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (2.528, 2.559, 2.592), stdev = 0.032
  CI (99.9%): [1.972, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
Iteration   3: 3.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.984, 3.004, 3.019), stdev = 0.018
  CI (99.9%): [2.670, 3.338] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.685 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  12.037 ms/op
                 createUser·p0.9999: 14.098 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.836 ms/op
                 createUser·p0.9999: 12.818 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.870 ms/op
                 createUser·p0.999:  8.280 ms/op
                 createUser·p0.9999: 11.338 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378480
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181691 
    [ 2.500,  3.750) = 192388 
    [ 3.750,  5.000) = 3444 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.336 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.687 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  5.873 ms/op
                 existUser·p0.9999: 13.627 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 18.071 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.672 ms/op
                 existUser·p0.999:  8.935 ms/op
                 existUser·p0.9999: 11.964 ms/op
                 existUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382707
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 186397 
    [ 2.500,  3.750) = 192759 
    [ 3.750,  5.000) = 2647 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.712 ms/op
     p(99.9900) =     15.105 ms/op
     p(99.9990) =     18.804 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  11.943 ms/op
                 getUser·p0.9999: 16.135 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  8.889 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.855 ms/op
                 getUser·p0.999:  6.903 ms/op
                 getUser·p0.9999: 11.459 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383186
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 189128 
    [ 2.500,  3.750) = 188961 
    [ 3.750,  5.000) = 4065 
    [ 5.000,  6.250) = 522 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.187 ms/op
     p(99.9900) =     13.960 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.954 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.583 ms/op
                 listUser·p0.999:  10.828 ms/op
                 listUser·p0.9999: 12.946 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 12.346 ms/op
                 listUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313688
  mean =      3.058 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 84084 
    [ 2.500,  3.750) = 187117 
    [ 3.750,  5.000) = 34704 
    [ 5.000,  6.250) = 6255 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 255 
    [ 8.750, 10.000) = 217 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.606 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     13.922 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.684 ± 2.344  ops/ms
ClientPb.existUser                       thrpt       3  12.967 ± 1.785  ops/ms
ClientPb.getUser                         thrpt       3  12.674 ± 1.114  ops/ms
ClientPb.listUser                        thrpt       3  10.611 ± 0.774  ops/ms
ClientPb.createUser                       avgt       3   2.591 ± 0.280   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.112   ms/op
ClientPb.getUser                          avgt       3   2.559 ± 0.587   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.334   ms/op
ClientPb.createUser                     sample  378480   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.336           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  382707   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.105           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.104           ms/op
ClientPb.getUser                        sample  383186   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.881           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.187           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.777           ms/op
ClientPb.listUser                       sample  313688   3.058 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.606           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
