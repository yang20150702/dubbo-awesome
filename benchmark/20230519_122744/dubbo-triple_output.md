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
# Warmup Iteration   1: 2.099 ops/ms
# Warmup Iteration   2: 5.130 ops/ms
# Warmup Iteration   3: 8.307 ops/ms
Iteration   1: 9.170 ops/ms
Iteration   2: 9.241 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.254 ±(99.9%) 1.683 ops/ms [Average]
  (min, avg, max) = (9.170, 9.254, 9.353), stdev = 0.092
  CI (99.9%): [7.572, 10.937] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.678 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 9.622 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.915 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (9.816, 9.915, 10.038), stdev = 0.113
  CI (99.9%): [7.857, 11.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.897 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 8.636 ops/ms
Iteration   1: 9.519 ops/ms
Iteration   2: 8.897 ops/ms
Iteration   3: 8.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.101 ±(99.9%) 6.611 ops/ms [Average]
  (min, avg, max) = (8.887, 9.101, 9.519), stdev = 0.362
  CI (99.9%): [2.490, 15.712] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 6.706 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.928 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (7.859, 7.928, 7.972), stdev = 0.061
  CI (99.9%): [6.814, 9.043] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.416 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.004 ms/op
Iteration   1: 3.435 ±(99.9%) 0.011 ms/op
Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
Iteration   3: 3.464 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.501 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.435, 3.501, 3.604), stdev = 0.091
  CI (99.9%): [1.844, 5.158] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.695 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.004 ms/op
Iteration   1: 3.298 ±(99.9%) 0.006 ms/op
Iteration   2: 3.258 ±(99.9%) 0.010 ms/op
Iteration   3: 3.480 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.346 ±(99.9%) 2.158 ms/op [Average]
  (min, avg, max) = (3.258, 3.346, 3.480), stdev = 0.118
  CI (99.9%): [1.188, 5.503] (assumes normal distribution)


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
# Warmup Iteration   1: 9.160 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.005 ms/op
Iteration   1: 3.415 ±(99.9%) 0.006 ms/op
Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
Iteration   3: 3.352 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.352, 3.378, 3.415), stdev = 0.033
  CI (99.9%): [2.776, 3.980] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.588 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
Iteration   2: 4.084 ±(99.9%) 0.008 ms/op
Iteration   3: 4.071 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.045 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (3.980, 4.045, 4.084), stdev = 0.057
  CI (99.9%): [3.013, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 10.307 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.015 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.980 ms/op
                 createUser·p0.9999: 23.512 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.384 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  26.867 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  18.097 ms/op
                 createUser·p0.9999: 25.416 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281137
  mean =      3.412 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9060 
    [ 2.500,  5.000) = 266374 
    [ 5.000,  7.500) = 4805 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     29.745 ms/op
     p(99.9990) =     32.996 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.916 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
Iteration   1: 3.334 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.526 ms/op
                 existUser·p0.999:  11.521 ms/op
                 existUser·p0.9999: 24.289 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.603 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.329 ms/op
                 existUser·p0.999:  24.126 ms/op
                 existUser·p0.9999: 27.452 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 3.440 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.725 ms/op
                 existUser·p0.999:  24.748 ms/op
                 existUser·p0.9999: 33.250 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277491
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8936 
    [ 2.500,  5.000) = 261123 
    [ 5.000,  7.500) = 6374 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     31.236 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 8.191 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
Iteration   1: 3.477 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  20.088 ms/op
                 getUser·p0.9999: 23.213 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.411 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.593 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.581 ms/op
                 getUser·p0.999:  20.186 ms/op
                 getUser·p0.9999: 28.934 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274651
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14450 
    [ 2.500,  5.000) = 247153 
    [ 5.000,  7.500) = 11801 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     20.164 ms/op
     p(99.9900) =     26.166 ms/op
     p(99.9990) =     30.417 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 11.407 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.014 ms/op
Iteration   1: 3.992 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 25.262 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  16.043 ms/op
                 listUser·p0.9999: 19.929 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 4.080 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.798 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237947
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 229641 
    [ 5.000,  7.500) = 5654 
    [ 7.500, 10.000) = 1468 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     16.500 ms/op
     p(99.9900) =     24.353 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.254 ± 1.683  ops/ms
ClientPb.existUser                       thrpt       3   9.915 ± 2.059  ops/ms
ClientPb.getUser                         thrpt       3   9.101 ± 6.611  ops/ms
ClientPb.listUser                        thrpt       3   7.928 ± 1.115  ops/ms
ClientPb.createUser                       avgt       3   3.501 ± 1.657   ms/op
ClientPb.existUser                        avgt       3   3.346 ± 2.158   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 0.602   ms/op
ClientPb.listUser                         avgt       3   4.045 ± 1.032   ms/op
ClientPb.createUser                     sample  281137   3.412 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.004           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.745           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.325           ms/op
ClientPb.existUser                      sample  277491   3.456 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.565           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.236           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  274651   3.492 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.081           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.166           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  237947   4.033 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.683           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.353           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
