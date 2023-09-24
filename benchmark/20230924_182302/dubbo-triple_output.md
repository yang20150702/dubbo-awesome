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
# Warmup Iteration   1: 1.915 ops/ms
# Warmup Iteration   2: 4.148 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.266 ops/ms
Iteration   3: 8.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.278 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (8.196, 8.278, 8.371), stdev = 0.088
  CI (99.9%): [6.672, 9.884] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.821 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.719 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 9.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.027 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (8.958, 9.027, 9.113), stdev = 0.079
  CI (99.9%): [7.587, 10.467] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.940 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 8.309 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.521 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (8.508, 8.521, 8.547), stdev = 0.023
  CI (99.9%): [8.110, 8.933] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 6.585 ops/ms
# Warmup Iteration   3: 7.015 ops/ms
Iteration   1: 6.976 ops/ms
Iteration   2: 7.163 ops/ms
Iteration   3: 7.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.094 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (6.976, 7.094, 7.163), stdev = 0.103
  CI (99.9%): [5.220, 8.969] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.209 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.007 ms/op
Iteration   1: 3.927 ±(99.9%) 0.005 ms/op
Iteration   2: 3.789 ±(99.9%) 0.006 ms/op
Iteration   3: 3.855 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.857 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.789, 3.857, 3.927), stdev = 0.069
  CI (99.9%): [2.591, 5.122] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.567 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.003 ms/op
Iteration   1: 3.560 ±(99.9%) 0.005 ms/op
Iteration   2: 3.638 ±(99.9%) 0.005 ms/op
Iteration   3: 3.653 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.617 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.560, 3.617, 3.653), stdev = 0.050
  CI (99.9%): [2.699, 4.535] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.358 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.003 ms/op
Iteration   1: 3.770 ±(99.9%) 0.004 ms/op
Iteration   2: 3.820 ±(99.9%) 0.005 ms/op
Iteration   3: 3.713 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.768 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.713, 3.768, 3.820), stdev = 0.053
  CI (99.9%): [2.793, 4.742] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.688 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.566 ±(99.9%) 0.007 ms/op
Iteration   1: 4.489 ±(99.9%) 0.012 ms/op
Iteration   2: 4.354 ±(99.9%) 0.012 ms/op
Iteration   3: 4.417 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.420 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (4.354, 4.420, 4.489), stdev = 0.068
  CI (99.9%): [3.184, 5.657] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.933 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.017 ms/op
Iteration   1: 3.801 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  22.315 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  15.887 ms/op
                 createUser·p0.9999: 27.437 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.677 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  23.068 ms/op
                 createUser·p0.9999: 31.608 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254662
  mean =      3.769 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1406 
    [ 2.500,  5.000) = 245125 
    [ 5.000,  7.500) = 6561 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     30.265 ms/op
     p(99.9990) =     32.580 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 10.293 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.010 ms/op
Iteration   1: 3.602 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  9.145 ms/op
                 existUser·p0.9999: 23.841 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.625 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  22.856 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.628 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 28.383 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265256
  mean =      3.618 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1286 
    [ 2.500,  5.000) = 257245 
    [ 5.000,  7.500) = 5404 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.516 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     27.342 ms/op
     p(99.9990) =     28.793 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.931 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.013 ms/op
Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  21.678 ms/op
                 getUser·p0.9999: 25.032 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 3.600 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  9.603 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.675 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  24.933 ms/op
                 getUser·p0.9999: 28.780 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261361
  mean =      3.669 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1050 
    [ 2.500,  5.000) = 254405 
    [ 5.000,  7.500) = 4535 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 114 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     20.698 ms/op
     p(99.9900) =     27.521 ms/op
     p(99.9990) =     29.143 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.646 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 5.068 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.689 ±(99.9%) 0.014 ms/op
Iteration   1: 4.644 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  23.673 ms/op
                 listUser·p0.9999: 27.278 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.655 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.365 ms/op
                 listUser·p0.999:  18.000 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.501 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 19.690 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208517
  mean =      4.599 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 177638 
    [ 5.000,  7.500) = 27797 
    [ 7.500, 10.000) = 2102 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 300 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     18.268 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     28.553 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.278 ± 1.606  ops/ms
ClientPb.existUser                       thrpt       3   9.027 ± 1.440  ops/ms
ClientPb.getUser                         thrpt       3   8.521 ± 0.412  ops/ms
ClientPb.listUser                        thrpt       3   7.094 ± 1.874  ops/ms
ClientPb.createUser                       avgt       3   3.857 ± 1.266   ms/op
ClientPb.existUser                        avgt       3   3.617 ± 0.918   ms/op
ClientPb.getUser                          avgt       3   3.768 ± 0.974   ms/op
ClientPb.listUser                         avgt       3   4.420 ± 1.236   ms/op
ClientPb.createUser                     sample  254662   3.769 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.758           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.265           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  265256   3.618 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.516           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.342           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.901           ms/op
ClientPb.getUser                        sample  261361   3.669 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.698           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  208517   4.599 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.268           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.836           ms/op
