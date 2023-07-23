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
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 8.779 ops/ms
Iteration   1: 9.726 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.563 ±(99.9%) 4.837 ops/ms [Average]
  (min, avg, max) = (9.258, 9.563, 9.726), stdev = 0.265
  CI (99.9%): [4.727, 14.400] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.002 ops/ms
# Warmup Iteration   2: 8.453 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.686 ops/ms
Iteration   2: 9.820 ops/ms
Iteration   3: 9.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.825 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (9.686, 9.825, 9.968), stdev = 0.141
  CI (99.9%): [7.253, 12.397] (assumes normal distribution)


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
# Warmup Iteration   1: 2.965 ops/ms
# Warmup Iteration   2: 7.965 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.700 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (9.664, 9.700, 9.730), stdev = 0.033
  CI (99.9%): [9.096, 10.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.168 ops/ms
# Warmup Iteration   2: 7.031 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 8.084 ops/ms
Iteration   2: 8.341 ops/ms
Iteration   3: 8.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.258 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (8.084, 8.258, 8.348), stdev = 0.150
  CI (99.9%): [5.519, 10.997] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.426 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.006 ms/op
Iteration   2: 3.429 ±(99.9%) 0.007 ms/op
Iteration   3: 3.203 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 2.166 ms/op [Average]
  (min, avg, max) = (3.203, 3.295, 3.429), stdev = 0.119
  CI (99.9%): [1.130, 5.461] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.746 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.005 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
Iteration   3: 3.354 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 2.388 ms/op [Average]
  (min, avg, max) = (3.111, 3.204, 3.354), stdev = 0.131
  CI (99.9%): [0.816, 5.592] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.234 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.003 ms/op
Iteration   1: 3.278 ±(99.9%) 0.003 ms/op
Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
Iteration   3: 3.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.391 ±(99.9%) 1.826 ms/op [Average]
  (min, avg, max) = (3.278, 3.391, 3.469), stdev = 0.100
  CI (99.9%): [1.565, 5.218] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.253 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
Iteration   1: 3.817 ±(99.9%) 0.012 ms/op
Iteration   2: 3.796 ±(99.9%) 0.011 ms/op
Iteration   3: 3.856 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.823 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.796, 3.823, 3.856), stdev = 0.031
  CI (99.9%): [3.263, 4.383] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.371 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.015 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  15.758 ms/op
                 createUser·p0.9999: 23.923 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 3.324 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  21.183 ms/op
                 createUser·p0.9999: 30.880 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  17.978 ms/op
                 createUser·p0.9999: 27.951 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290942
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12171 
    [ 2.500,  5.000) = 273829 
    [ 5.000,  7.500) = 3996 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     16.157 ms/op
     p(99.9900) =     30.105 ms/op
     p(99.9990) =     32.226 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.769 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  12.283 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.187 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  19.333 ms/op
                 existUser·p0.9999: 31.161 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.263 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  16.531 ms/op
                 existUser·p0.9999: 28.383 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297522
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13836 
    [ 2.500,  5.000) = 277932 
    [ 5.000,  7.500) = 4625 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     16.383 ms/op
     p(99.9900) =     29.704 ms/op
     p(99.9990) =     31.753 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 8.583 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.012 ms/op
Iteration   1: 3.630 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  21.006 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  22.413 ms/op
                 getUser·p0.9999: 27.045 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  10.836 ms/op
                 getUser·p0.9999: 28.550 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278316
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9067 
    [ 2.500,  5.000) = 258258 
    [ 5.000,  7.500) = 9439 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     15.478 ms/op
     p(99.9900) =     27.498 ms/op
     p(99.9990) =     29.105 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 10.763 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.018 ms/op
Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 25.979 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.165 ms/op
                 listUser·p0.9999: 32.604 ms/op
                 listUser·p1.00:   32.670 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.737 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 20.203 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244499
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 235438 
    [ 5.000,  7.500) = 6331 
    [ 7.500, 10.000) = 1731 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.563 ± 4.837  ops/ms
ClientPb.existUser                       thrpt       3   9.825 ± 2.572  ops/ms
ClientPb.getUser                         thrpt       3   9.700 ± 0.604  ops/ms
ClientPb.listUser                        thrpt       3   8.258 ± 2.739  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 2.166   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 2.388   ms/op
ClientPb.getUser                          avgt       3   3.391 ± 1.826   ms/op
ClientPb.listUser                         avgt       3   3.823 ± 0.560   ms/op
ClientPb.createUser                     sample  290942   3.297 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.157           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.105           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  297522   3.222 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.413           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.383           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.704           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  278316   3.448 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.478           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  244499   3.923 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.089           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.588           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.670           ms/op
