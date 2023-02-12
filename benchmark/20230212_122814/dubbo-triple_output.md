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
# Warmup Iteration   1: 2.686 ops/ms
# Warmup Iteration   2: 6.877 ops/ms
# Warmup Iteration   3: 9.312 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 9.996 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.051 ±(99.9%) 5.220 ops/ms [Average]
  (min, avg, max) = (9.797, 10.051, 10.361), stdev = 0.286
  CI (99.9%): [4.831, 15.272] (assumes normal distribution)


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
# Warmup Iteration   1: 3.558 ops/ms
# Warmup Iteration   2: 9.711 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.198 ±(99.9%) 4.928 ops/ms [Average]
  (min, avg, max) = (9.932, 10.198, 10.472), stdev = 0.270
  CI (99.9%): [5.270, 15.125] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ops/ms
# Warmup Iteration   2: 8.123 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 9.742 ops/ms
Iteration   2: 10.175 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.869 ±(99.9%) 4.859 ops/ms [Average]
  (min, avg, max) = (9.689, 9.869, 10.175), stdev = 0.266
  CI (99.9%): [5.010, 14.728] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ops/ms
# Warmup Iteration   2: 7.644 ops/ms
# Warmup Iteration   3: 8.125 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.788 ops/ms
Iteration   3: 8.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 5.476 ops/ms [Average]
  (min, avg, max) = (8.221, 8.561, 8.788), stdev = 0.300
  CI (99.9%): [3.085, 14.038] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.276 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.152 ±(99.9%) 0.010 ms/op
Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
Iteration   3: 3.125 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.125, 3.137, 3.152), stdev = 0.014
  CI (99.9%): [2.883, 3.390] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.387 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.029 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.993, 3.029, 3.059), stdev = 0.033
  CI (99.9%): [2.425, 3.632] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.260 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.005 ms/op
Iteration   1: 3.209 ±(99.9%) 0.005 ms/op
Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.186 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.170, 3.186, 3.209), stdev = 0.021
  CI (99.9%): [2.803, 3.568] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.114 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
Iteration   1: 3.724 ±(99.9%) 0.008 ms/op
Iteration   2: 3.696 ±(99.9%) 0.009 ms/op
Iteration   3: 3.821 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.747 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.696, 3.747, 3.821), stdev = 0.066
  CI (99.9%): [2.547, 4.947] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.361 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.278 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  12.883 ms/op
                 createUser·p0.9999: 22.389 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.215 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  10.883 ms/op
                 createUser·p0.9999: 22.827 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   6.100 ms/op
                 createUser·p0.999:  17.530 ms/op
                 createUser·p0.9999: 23.028 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303180
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26332 
    [ 2.500,  5.000) = 271711 
    [ 5.000,  7.500) = 4401 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.642 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 6.880 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
Iteration   1: 3.271 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 26.748 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  15.843 ms/op
                 existUser·p0.9999: 24.176 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.164 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 22.541 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300942
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16883 
    [ 2.500,  5.000) = 278074 
    [ 5.000,  7.500) = 5075 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.174 ms/op
     p(99.9900) =     25.010 ms/op
     p(99.9990) =     27.459 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 8.010 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.011 ms/op
Iteration   1: 3.301 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  13.891 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  10.884 ms/op
                 getUser·p0.9999: 21.922 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  14.391 ms/op
                 getUser·p0.9999: 20.899 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302693
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13529 
    [ 2.500,  5.000) = 282029 
    [ 5.000,  7.500) = 6202 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     13.804 ms/op
     p(99.9900) =     23.853 ms/op
     p(99.9990) =     25.881 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 8.387 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.011 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.561 ms/op
                 listUser·p0.9999: 22.593 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.684 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.356 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.655 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.067 ms/op
                 listUser·p0.99:   6.695 ms/op
                 listUser·p0.999:  11.977 ms/op
                 listUser·p0.9999: 16.736 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259413
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 253411 
    [ 5.000,  7.500) = 4150 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     21.309 ms/op
     p(99.9990) =     23.243 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.051 ± 5.220  ops/ms
ClientPb.existUser                       thrpt       3  10.198 ± 4.928  ops/ms
ClientPb.getUser                         thrpt       3   9.869 ± 4.859  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 5.476  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 0.254   ms/op
ClientPb.existUser                        avgt       3   3.029 ± 0.604   ms/op
ClientPb.getUser                          avgt       3   3.186 ± 0.382   ms/op
ClientPb.listUser                         avgt       3   3.747 ± 1.200   ms/op
ClientPb.createUser                     sample  303180   3.165 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.278           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.712           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  300942   3.187 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.010           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.656           ms/op
ClientPb.getUser                        sample  302693   3.170 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.748           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.853           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  259413   3.698 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.587           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.309           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
