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
# Warmup Iteration   1: 2.577 ops/ms
# Warmup Iteration   2: 5.351 ops/ms
# Warmup Iteration   3: 9.070 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.849 ±(99.9%) 3.320 ops/ms [Average]
  (min, avg, max) = (9.744, 9.849, 10.060), stdev = 0.182
  CI (99.9%): [6.529, 13.170] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 10.009 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.419 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (10.359, 10.419, 10.472), stdev = 0.057
  CI (99.9%): [9.378, 11.459] (assumes normal distribution)


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
# Warmup Iteration   1: 3.407 ops/ms
# Warmup Iteration   2: 9.302 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.893 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (9.797, 9.893, 9.944), stdev = 0.083
  CI (99.9%): [8.373, 11.413] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.179 ops/ms
# Warmup Iteration   2: 7.611 ops/ms
# Warmup Iteration   3: 8.460 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.546 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (8.509, 8.546, 8.588), stdev = 0.040
  CI (99.9%): [7.818, 9.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.815 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.005 ms/op
Iteration   1: 3.301 ±(99.9%) 0.006 ms/op
Iteration   2: 3.443 ±(99.9%) 0.005 ms/op
Iteration   3: 3.190 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.312 ±(99.9%) 2.317 ms/op [Average]
  (min, avg, max) = (3.190, 3.312, 3.443), stdev = 0.127
  CI (99.9%): [0.994, 5.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.983 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
Iteration   3: 3.027 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.109 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (3.027, 3.109, 3.150), stdev = 0.071
  CI (99.9%): [1.813, 4.404] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.599 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.003 ms/op
Iteration   1: 3.293 ±(99.9%) 0.003 ms/op
Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
Iteration   3: 3.250 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.184, 3.243, 3.293), stdev = 0.055
  CI (99.9%): [2.242, 4.243] (assumes normal distribution)


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
# Warmup Iteration   1: 10.029 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.005 ms/op
Iteration   1: 3.852 ±(99.9%) 0.008 ms/op
Iteration   2: 3.764 ±(99.9%) 0.007 ms/op
Iteration   3: 3.823 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.813 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.764, 3.813, 3.852), stdev = 0.045
  CI (99.9%): [2.997, 4.629] (assumes normal distribution)


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
# Warmup Iteration   1: 8.746 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
Iteration   1: 3.201 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  13.009 ms/op
                 createUser·p0.9999: 38.929 ms/op
                 createUser·p1.00:   39.911 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  20.492 ms/op
                 createUser·p0.9999: 27.559 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.540 ms/op
                 createUser·p0.999:  15.785 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299115
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12728 
    [ 2.500,  5.000) = 281064 
    [ 5.000,  7.500) = 4582 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     38.344 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 7.469 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  9.735 ms/op
                 existUser·p0.9999: 20.703 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  14.383 ms/op
                 existUser·p0.9999: 25.742 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.064 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.855 ms/op
                 existUser·p0.9999: 20.572 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306211
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10231 
    [ 2.500,  5.000) = 290999 
    [ 5.000,  7.500) = 4159 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     10.793 ms/op
     p(99.9900) =     24.003 ms/op
     p(99.9990) =     26.180 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.010 ms/op
Iteration   1: 3.220 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 19.729 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.588 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  15.663 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296672
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17516 
    [ 2.500,  5.000) = 272314 
    [ 5.000,  7.500) = 6065 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     16.340 ms/op
     p(99.9900) =     21.245 ms/op
     p(99.9990) =     23.726 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 9.333 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.011 ms/op
Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.394 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.690 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.706 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.264 ms/op
                 listUser·p0.9999: 15.233 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256031
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 247998 
    [ 5.000,  7.500) = 6025 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     21.394 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.849 ± 3.320  ops/ms
ClientPb.existUser                       thrpt       3  10.419 ± 1.040  ops/ms
ClientPb.getUser                         thrpt       3   9.893 ± 1.520  ops/ms
ClientPb.listUser                        thrpt       3   8.546 ± 0.727  ops/ms
ClientPb.createUser                       avgt       3   3.312 ± 2.317   ms/op
ClientPb.existUser                        avgt       3   3.109 ± 1.295   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 1.001   ms/op
ClientPb.listUser                         avgt       3   3.813 ± 0.816   ms/op
ClientPb.createUser                     sample  299115   3.205 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.139           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.876           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.911           ms/op
ClientPb.existUser                      sample  306211   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.003           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.247           ms/op
ClientPb.getUser                        sample  296672   3.233 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.340           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  256031   3.750 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.346           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.463           ms/op
