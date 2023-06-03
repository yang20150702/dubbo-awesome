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
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 6.594 ops/ms
# Warmup Iteration   3: 8.988 ops/ms
Iteration   1: 9.701 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 10.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.863 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (9.701, 9.863, 10.005), stdev = 0.153
  CI (99.9%): [7.072, 12.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ops/ms
# Warmup Iteration   2: 9.603 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.529 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (10.457, 10.529, 10.643), stdev = 0.100
  CI (99.9%): [8.702, 12.355] (assumes normal distribution)


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
# Warmup Iteration   1: 3.346 ops/ms
# Warmup Iteration   2: 8.745 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 9.695 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.991 ±(99.9%) 4.849 ops/ms [Average]
  (min, avg, max) = (9.695, 9.991, 10.208), stdev = 0.266
  CI (99.9%): [5.142, 14.841] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 8.622 ops/ms
Iteration   1: 8.785 ops/ms
Iteration   2: 8.454 ops/ms
Iteration   3: 8.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.605 ±(99.9%) 3.053 ops/ms [Average]
  (min, avg, max) = (8.454, 8.605, 8.785), stdev = 0.167
  CI (99.9%): [5.552, 11.659] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.606 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.004 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
Iteration   3: 3.101 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.242 ±(99.9%) 2.234 ms/op [Average]
  (min, avg, max) = (3.101, 3.242, 3.321), stdev = 0.122
  CI (99.9%): [1.008, 5.476] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.179 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.004 ms/op
Iteration   1: 3.156 ±(99.9%) 0.006 ms/op
Iteration   2: 3.289 ±(99.9%) 0.004 ms/op
Iteration   3: 3.113 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.186 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (3.113, 3.186, 3.289), stdev = 0.092
  CI (99.9%): [1.505, 4.867] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.005 ms/op
Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
Iteration   3: 3.140 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.127 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (3.116, 3.127, 3.140), stdev = 0.012
  CI (99.9%): [2.902, 3.351] (assumes normal distribution)


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
# Warmup Iteration   1: 8.619 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.005 ms/op
Iteration   1: 3.678 ±(99.9%) 0.009 ms/op
Iteration   2: 3.664 ±(99.9%) 0.006 ms/op
Iteration   3: 3.706 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.682 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.664, 3.682, 3.706), stdev = 0.021
  CI (99.9%): [3.292, 4.073] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  20.353 ms/op
                 createUser·p0.9999: 23.129 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.168 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  16.914 ms/op
                 createUser·p0.9999: 29.688 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305411
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25286 
    [ 2.500,  5.000) = 276177 
    [ 5.000,  7.500) = 3084 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     18.323 ms/op
     p(99.9900) =     29.063 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 7.274 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 19.995 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.410 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.131 ms/op
                 existUser·p0.9999: 23.499 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.534 ms/op
                 existUser·p0.9999: 21.748 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311261
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16737 
    [ 2.500,  5.000) = 290157 
    [ 5.000,  7.500) = 3587 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     12.607 ms/op
     p(99.9900) =     22.606 ms/op
     p(99.9990) =     24.073 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 7.811 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
Iteration   1: 3.339 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 20.311 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.742 ms/op
                 getUser·p0.9999: 21.759 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294223
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6008 
    [ 2.500,  5.000) = 278855 
    [ 5.000,  7.500) = 8156 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.190 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 8.116 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.012 ms/op
Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.743 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.149 ms/op
                 listUser·p0.9999: 14.393 ms/op
                 listUser·p1.00:   14.582 ms/op

Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255102
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 247032 
    [ 5.000,  7.500) = 6319 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     19.906 ms/op
     p(99.9990) =     20.837 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.863 ± 2.791  ops/ms
ClientPb.existUser                       thrpt       3  10.529 ± 1.826  ops/ms
ClientPb.getUser                         thrpt       3   9.991 ± 4.849  ops/ms
ClientPb.listUser                        thrpt       3   8.605 ± 3.053  ops/ms
ClientPb.createUser                       avgt       3   3.242 ± 2.234   ms/op
ClientPb.existUser                        avgt       3   3.186 ± 1.681   ms/op
ClientPb.getUser                          avgt       3   3.127 ± 0.224   ms/op
ClientPb.listUser                         avgt       3   3.682 ± 0.390   ms/op
ClientPb.createUser                     sample  305411   3.140 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.909           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.323           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  311261   3.084 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.734           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.607           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  294223   3.261 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.040           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.446           ms/op
ClientPb.listUser                       sample  255102   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.697           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.906           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.906           ms/op
