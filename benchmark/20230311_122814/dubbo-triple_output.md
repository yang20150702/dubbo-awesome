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
# Warmup Iteration   1: 2.648 ops/ms
# Warmup Iteration   2: 5.739 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 8.911 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.637 ±(99.9%) 12.178 ops/ms [Average]
  (min, avg, max) = (8.911, 9.637, 10.225), stdev = 0.668
  CI (99.9%): [≈ 0, 21.814] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ops/ms
# Warmup Iteration   2: 9.793 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.244 ops/ms
Iteration   3: 10.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.497 ±(99.9%) 4.069 ops/ms [Average]
  (min, avg, max) = (10.244, 10.497, 10.667), stdev = 0.223
  CI (99.9%): [6.428, 14.566] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 9.057 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 10.141 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 10.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.034 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (9.939, 10.034, 10.141), stdev = 0.102
  CI (99.9%): [8.181, 11.886] (assumes normal distribution)


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
# Warmup Iteration   1: 3.368 ops/ms
# Warmup Iteration   2: 8.096 ops/ms
# Warmup Iteration   3: 8.305 ops/ms
Iteration   1: 8.684 ops/ms
Iteration   2: 8.677 ops/ms
Iteration   3: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.606 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (8.456, 8.606, 8.684), stdev = 0.130
  CI (99.9%): [6.237, 10.974] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.863 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.240 ±(99.9%) 0.006 ms/op
Iteration   3: 3.237 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.103, 3.193, 3.240), stdev = 0.078
  CI (99.9%): [1.763, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 6.796 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.005 ms/op
Iteration   1: 2.954 ±(99.9%) 0.004 ms/op
Iteration   2: 3.050 ±(99.9%) 0.004 ms/op
Iteration   3: 3.093 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.032 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (2.954, 3.032, 3.093), stdev = 0.071
  CI (99.9%): [1.730, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 7.899 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.004 ms/op
Iteration   1: 3.217 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.001 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.130 ±(99.9%) 1.455 ms/op [Average]
  (min, avg, max) = (3.061, 3.130, 3.217), stdev = 0.080
  CI (99.9%): [1.675, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 9.391 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.004 ms/op
Iteration   1: 3.714 ±(99.9%) 0.008 ms/op
Iteration   2: 3.590 ±(99.9%) 0.010 ms/op
Iteration   3: 3.614 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.640 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (3.590, 3.640, 3.714), stdev = 0.066
  CI (99.9%): [2.438, 4.841] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
Iteration   1: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  18.052 ms/op
                 createUser·p0.9999: 19.795 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.458 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  12.975 ms/op
                 createUser·p0.9999: 24.894 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  13.238 ms/op
                 createUser·p0.9999: 18.805 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303323
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21266 
    [ 2.500,  5.000) = 277792 
    [ 5.000,  7.500) = 3458 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     15.494 ms/op
     p(99.9900) =     24.041 ms/op
     p(99.9990) =     25.457 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.045 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  11.527 ms/op
                 existUser·p0.9999: 21.603 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  10.295 ms/op
                 existUser·p0.9999: 19.503 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312262
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21290 
    [ 2.500,  5.000) = 286347 
    [ 5.000,  7.500) = 3963 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.259 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 7.585 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.010 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 22.931 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  8.850 ms/op
                 getUser·p0.9999: 23.688 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304183
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8788 
    [ 2.500,  5.000) = 289433 
    [ 5.000,  7.500) = 5130 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.826 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     23.252 ms/op
     p(99.9990) =     23.821 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 8.427 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 20.360 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.524 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.694 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  13.310 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259055
  mean =      3.704 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 251926 
    [ 5.000,  7.500) = 5185 
    [ 7.500, 10.000) = 1205 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     19.066 ms/op
     p(99.9990) =     20.809 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.637 ± 12.178  ops/ms
ClientPb.existUser                       thrpt       3  10.497 ±  4.069  ops/ms
ClientPb.getUser                         thrpt       3  10.034 ±  1.853  ops/ms
ClientPb.listUser                        thrpt       3   8.606 ±  2.368  ops/ms
ClientPb.createUser                       avgt       3   3.193 ±  1.430   ms/op
ClientPb.existUser                        avgt       3   3.032 ±  1.303   ms/op
ClientPb.getUser                          avgt       3   3.130 ±  1.455   ms/op
ClientPb.listUser                         avgt       3   3.640 ±  1.201   ms/op
ClientPb.createUser                     sample  303323   3.159 ±  0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.942            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.543            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.494            ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.041            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018            ms/op
ClientPb.existUser                      sample  312262   3.072 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284            ms/op
ClientPb.existUser:existUser·p0.999     sample          11.259            ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.168            ms/op
ClientPb.existUser:existUser·p1.00      sample          22.905            ms/op
ClientPb.getUser                        sample  304183   3.153 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.313            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.011            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.826            ms/op
ClientPb.getUser:getUser·p0.999         sample          16.122            ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.252            ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052            ms/op
ClientPb.listUser                       sample  259055   3.704 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.948            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604            ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922            ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861            ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.066            ms/op
ClientPb.listUser:listUser·p1.00        sample          20.939            ms/op
