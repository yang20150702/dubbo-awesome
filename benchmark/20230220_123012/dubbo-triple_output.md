# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 5.945 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.664 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.858 ±(99.9%) 3.854 ops/ms [Average]
  (min, avg, max) = (9.664, 9.858, 10.083), stdev = 0.211
  CI (99.9%): [6.004, 13.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ops/ms
# Warmup Iteration   2: 8.755 ops/ms
# Warmup Iteration   3: 9.867 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.221 ±(99.9%) 4.382 ops/ms [Average]
  (min, avg, max) = (10.029, 10.221, 10.491), stdev = 0.240
  CI (99.9%): [5.839, 14.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.738 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.979 ±(99.9%) 5.320 ops/ms [Average]
  (min, avg, max) = (9.738, 9.979, 10.303), stdev = 0.292
  CI (99.9%): [4.659, 15.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ops/ms
# Warmup Iteration   2: 7.906 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.405 ops/ms
Iteration   2: 8.370 ops/ms
Iteration   3: 8.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.465 ±(99.9%) 2.479 ops/ms [Average]
  (min, avg, max) = (8.370, 8.465, 8.621), stdev = 0.136
  CI (99.9%): [5.986, 10.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.333 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.005 ms/op
Iteration   2: 3.390 ±(99.9%) 0.005 ms/op
Iteration   3: 3.335 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.324 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.249, 3.324, 3.390), stdev = 0.071
  CI (99.9%): [2.030, 4.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.241 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.263 ±(99.9%) 0.004 ms/op
Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 1.608 ms/op [Average]
  (min, avg, max) = (3.086, 3.177, 3.263), stdev = 0.088
  CI (99.9%): [1.569, 4.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.524 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.004 ms/op
Iteration   1: 3.272 ±(99.9%) 0.005 ms/op
Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
Iteration   3: 3.224 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (3.203, 3.233, 3.272), stdev = 0.035
  CI (99.9%): [2.588, 3.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.589 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.008 ms/op
Iteration   1: 3.811 ±(99.9%) 0.009 ms/op
Iteration   2: 3.905 ±(99.9%) 0.005 ms/op
Iteration   3: 3.665 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.794 ±(99.9%) 2.206 ms/op [Average]
  (min, avg, max) = (3.665, 3.794, 3.905), stdev = 0.121
  CI (99.9%): [1.587, 6.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.838 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  14.466 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 21.981 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302782
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14779 
    [ 2.500,  5.000) = 282633 
    [ 5.000,  7.500) = 4391 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.457 ms/op
     p(99.9900) =     25.710 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.626 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  14.582 ms/op
                 existUser·p0.9999: 24.034 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  14.746 ms/op
                 existUser·p0.9999: 24.564 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 20.148 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309412
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22018 
    [ 2.500,  5.000) = 281667 
    [ 5.000,  7.500) = 4880 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     24.119 ms/op
     p(99.9990) =     24.901 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  16.133 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293710
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18741 
    [ 2.500,  5.000) = 266162 
    [ 5.000,  7.500) = 7853 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     21.353 ms/op
     p(99.9990) =     23.106 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.736 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.013 ms/op
Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 3.804 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 16.771 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.794 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 18.382 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250505
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 239892 
    [ 5.000,  7.500) = 8384 
    [ 7.500, 10.000) = 1448 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.461 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.858 ± 3.854  ops/ms
ClientPb.existUser                       thrpt       3  10.221 ± 4.382  ops/ms
ClientPb.getUser                         thrpt       3   9.979 ± 5.320  ops/ms
ClientPb.listUser                        thrpt       3   8.465 ± 2.479  ops/ms
ClientPb.createUser                       avgt       3   3.324 ± 1.294   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 1.608   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 0.645   ms/op
ClientPb.listUser                         avgt       3   3.794 ± 2.206   ms/op
ClientPb.createUser                     sample  302782   3.171 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.457           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.672           ms/op
ClientPb.existUser                      sample  309412   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.500           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.119           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  293710   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.984           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  250505   3.828 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.550           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
