# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
# Warmup Iteration   2: 6.057 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.022 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.218 ±(99.9%) 4.906 ops/ms [Average]
  (min, avg, max) = (9.022, 9.218, 9.524), stdev = 0.269
  CI (99.9%): [4.312, 14.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 8.555 ops/ms
# Warmup Iteration   3: 9.646 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.656 ±(99.9%) 3.945 ops/ms [Average]
  (min, avg, max) = (9.430, 9.656, 9.861), stdev = 0.216
  CI (99.9%): [5.711, 13.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 8.767 ops/ms
# Warmup Iteration   3: 8.787 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 8.966 ops/ms
Iteration   3: 9.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.134 ±(99.9%) 3.569 ops/ms [Average]
  (min, avg, max) = (8.966, 9.134, 9.349), stdev = 0.196
  CI (99.9%): [5.565, 12.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.962 ops/ms
# Warmup Iteration   2: 7.082 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.864 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (7.802, 7.864, 7.913), stdev = 0.057
  CI (99.9%): [6.831, 8.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.821 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.008 ms/op
Iteration   1: 3.562 ±(99.9%) 0.006 ms/op
Iteration   2: 3.510 ±(99.9%) 0.009 ms/op
Iteration   3: 3.454 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.509 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.454, 3.509, 3.562), stdev = 0.054
  CI (99.9%): [2.524, 4.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.003 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op
Iteration   2: 3.316 ±(99.9%) 0.005 ms/op
Iteration   3: 3.285 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.300 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.285, 3.300, 3.316), stdev = 0.016
  CI (99.9%): [3.009, 3.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.880 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.003 ms/op
Iteration   1: 3.608 ±(99.9%) 0.006 ms/op
Iteration   2: 3.473 ±(99.9%) 0.006 ms/op
Iteration   3: 3.516 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.532 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.473, 3.532, 3.608), stdev = 0.069
  CI (99.9%): [2.271, 4.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.489 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.014 ms/op
Iteration   1: 4.094 ±(99.9%) 0.016 ms/op
Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
Iteration   3: 4.055 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (4.026, 4.058, 4.094), stdev = 0.034
  CI (99.9%): [3.434, 4.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.606 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.013 ms/op
Iteration   1: 3.512 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.558 ms/op
                 createUser·p0.9999: 25.260 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 3.410 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.886 ms/op
                 createUser·p0.999:  21.332 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.611 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.736 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273589
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13005 
    [ 2.500,  5.000) = 253674 
    [ 5.000,  7.500) = 6185 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     19.740 ms/op
     p(99.9900) =     25.809 ms/op
     p(99.9990) =     26.675 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.021 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
Iteration   1: 3.396 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.743 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.887 ms/op
                 existUser·p0.9999: 21.613 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.258 ms/op
                 existUser·p0.9999: 29.091 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  19.864 ms/op
                 existUser·p0.9999: 25.362 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283668
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9967 
    [ 2.500,  5.000) = 267080 
    [ 5.000,  7.500) = 5657 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.855 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     29.436 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.949 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.010 ms/op
Iteration   1: 3.580 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  11.773 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  22.271 ms/op
                 getUser·p0.9999: 24.529 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  21.109 ms/op
                 getUser·p0.9999: 28.747 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272538
  mean =      3.521 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 969 
    [ 2.500,  5.000) = 261013 
    [ 5.000,  7.500) = 9218 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     13.515 ms/op
     p(99.9900) =     27.058 ms/op
     p(99.9990) =     29.697 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.067 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.869 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.014 ms/op
Iteration   1: 4.145 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  21.022 ms/op
                 listUser·p0.9999: 25.217 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 20.034 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 4.250 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  16.246 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231326
  mean =      4.145 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 221347 
    [ 5.000,  7.500) = 7402 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     17.782 ms/op
     p(99.9900) =     24.211 ms/op
     p(99.9990) =     26.161 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.218 ± 4.906  ops/ms
ClientPb.existUser                       thrpt       3   9.656 ± 3.945  ops/ms
ClientPb.getUser                         thrpt       3   9.134 ± 3.569  ops/ms
ClientPb.listUser                        thrpt       3   7.864 ± 1.032  ops/ms
ClientPb.createUser                       avgt       3   3.509 ± 0.984   ms/op
ClientPb.existUser                        avgt       3   3.300 ± 0.291   ms/op
ClientPb.getUser                          avgt       3   3.532 ± 1.261   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 0.625   ms/op
ClientPb.createUser                     sample  273589   3.509 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.809           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  283668   3.383 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.988           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.855           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.754           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.917           ms/op
ClientPb.getUser                        sample  272538   3.521 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  231326   4.145 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.782           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.211           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
