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
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 11.933 ops/ms
# Warmup Iteration   3: 12.236 ops/ms
Iteration   1: 12.471 ops/ms
Iteration   2: 12.530 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.533 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (12.471, 12.533, 12.599), stdev = 0.064
  CI (99.9%): [11.366, 13.700] (assumes normal distribution)


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
# Warmup Iteration   1: 7.933 ops/ms
# Warmup Iteration   2: 12.753 ops/ms
# Warmup Iteration   3: 12.936 ops/ms
Iteration   1: 12.890 ops/ms
Iteration   2: 12.987 ops/ms
Iteration   3: 13.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.964 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (12.890, 12.964, 13.013), stdev = 0.065
  CI (99.9%): [11.782, 14.145] (assumes normal distribution)


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
# Warmup Iteration   1: 7.574 ops/ms
# Warmup Iteration   2: 12.386 ops/ms
# Warmup Iteration   3: 12.573 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.742 ±(99.9%) 2.366 ops/ms [Average]
  (min, avg, max) = (12.597, 12.742, 12.847), stdev = 0.130
  CI (99.9%): [10.376, 15.108] (assumes normal distribution)


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
# Warmup Iteration   1: 6.847 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.715 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.786 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.697 ±(99.9%) 2.071 ops/ms [Average]
  (min, avg, max) = (10.569, 10.697, 10.786), stdev = 0.113
  CI (99.9%): [8.626, 12.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.514, 2.516, 2.519), stdev = 0.003
  CI (99.9%): [2.463, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.003 ms/op
Iteration   1: 2.424 ±(99.9%) 0.003 ms/op
Iteration   2: 2.425 ±(99.9%) 0.003 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.424, 2.434, 2.452), stdev = 0.016
  CI (99.9%): [2.148, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.477, 2.485, 2.490), stdev = 0.007
  CI (99.9%): [2.354, 2.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 3.007 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (3.005, 3.007, 3.010), stdev = 0.003
  CI (99.9%): [2.956, 3.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  12.108 ms/op
                 createUser·p0.9999: 14.268 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  7.828 ms/op
                 createUser·p0.9999: 12.618 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 12.173 ms/op
                 createUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382835
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 186174 
    [ 2.500,  3.750) = 191598 
    [ 3.750,  5.000) = 4137 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     13.955 ms/op
     p(99.9990) =     14.617 ms/op
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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  8.312 ms/op
                 existUser·p0.9999: 18.844 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.550 ms/op
                 existUser·p0.9999: 14.816 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 12.305 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388168
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 194729 
    [ 2.500,  3.750) = 189558 
    [ 3.750,  5.000) = 2943 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.782 ms/op
     p(99.9900) =     16.882 ms/op
     p(99.9990) =     19.406 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  12.078 ms/op
                 getUser·p0.9999: 17.527 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 14.287 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  8.213 ms/op
                 getUser·p0.9999: 10.912 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380914
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 187641 
    [ 2.500,  3.750) = 188242 
    [ 3.750,  5.000) = 4053 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.333 ms/op
     p(99.9900) =     15.441 ms/op
     p(99.9990) =     17.837 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.169 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 11.406 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.983 ms/op
                 listUser·p0.9999: 12.286 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318155
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 88738 
    [ 2.500,  3.750) = 189821 
    [ 3.750,  5.000) = 32837 
    [ 5.000,  6.250) = 5429 
    [ 6.250,  7.500) = 521 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     11.461 ms/op
     p(99.9990) =     13.481 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.533 ± 1.167  ops/ms
ClientPb.existUser                       thrpt       3  12.964 ± 1.182  ops/ms
ClientPb.getUser                         thrpt       3  12.742 ± 2.366  ops/ms
ClientPb.listUser                        thrpt       3  10.697 ± 2.071  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.053   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.132   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.052   ms/op
ClientPb.createUser                     sample  382835   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.094           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.955           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  388168   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.979           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.782           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.882           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.825           ms/op
ClientPb.getUser                        sample  380914   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.333           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.441           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.088           ms/op
ClientPb.listUser                       sample  318155   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.730           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.461           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
