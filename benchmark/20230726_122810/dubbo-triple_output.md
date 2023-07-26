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
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 5.697 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.967 ops/ms
Iteration   2: 9.040 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.078 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (8.967, 9.078, 9.226), stdev = 0.134
  CI (99.9%): [6.640, 11.515] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 8.316 ops/ms
# Warmup Iteration   3: 9.010 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 9.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.390 ±(99.9%) 0.573 ops/ms [Average]
  (min, avg, max) = (9.362, 9.390, 9.424), stdev = 0.031
  CI (99.9%): [8.817, 9.962] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.900 ops/ms
# Warmup Iteration   2: 8.053 ops/ms
# Warmup Iteration   3: 8.877 ops/ms
Iteration   1: 8.701 ops/ms
Iteration   2: 9.112 ops/ms
Iteration   3: 9.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.943 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (8.701, 8.943, 9.112), stdev = 0.215
  CI (99.9%): [5.021, 12.866] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 6.720 ops/ms
# Warmup Iteration   3: 7.308 ops/ms
Iteration   1: 7.660 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.822 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (7.660, 7.822, 8.007), stdev = 0.174
  CI (99.9%): [4.643, 11.001] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.676 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.004 ms/op
Iteration   1: 3.500 ±(99.9%) 0.007 ms/op
Iteration   2: 3.528 ±(99.9%) 0.004 ms/op
Iteration   3: 3.419 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.483 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.419, 3.483, 3.528), stdev = 0.057
  CI (99.9%): [2.452, 4.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.109 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.007 ms/op
Iteration   1: 3.329 ±(99.9%) 0.011 ms/op
Iteration   2: 3.421 ±(99.9%) 0.006 ms/op
Iteration   3: 3.329 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.360 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.329, 3.360, 3.421), stdev = 0.053
  CI (99.9%): [2.386, 4.334] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.998 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.004 ms/op
Iteration   1: 3.439 ±(99.9%) 0.006 ms/op
Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
Iteration   3: 3.575 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.517 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.439, 3.517, 3.575), stdev = 0.070
  CI (99.9%): [2.242, 4.791] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.000 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.004 ms/op
Iteration   1: 4.192 ±(99.9%) 0.008 ms/op
Iteration   2: 4.159 ±(99.9%) 0.009 ms/op
Iteration   3: 4.176 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.176 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (4.159, 4.176, 4.192), stdev = 0.017
  CI (99.9%): [3.874, 4.478] (assumes normal distribution)


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
# Warmup Iteration   1: 10.994 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.015 ms/op
Iteration   1: 3.620 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  22.281 ms/op
                 createUser·p0.9999: 26.449 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.527 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 29.784 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 3.619 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267491
  mean =      3.588 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7857 
    [ 2.500,  5.000) = 251024 
    [ 5.000,  7.500) = 6550 
    [ 7.500, 10.000) = 1161 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     33.768 ms/op
     p(99.9990) =     35.606 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.177 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   6.378 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 25.450 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  23.883 ms/op
                 existUser·p0.9999: 28.836 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 30.769 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279335
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2245 
    [ 2.500,  5.000) = 269329 
    [ 5.000,  7.500) = 5750 
    [ 7.500, 10.000) = 1400 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.534 ms/op
     p(99.9000) =     12.217 ms/op
     p(99.9900) =     29.432 ms/op
     p(99.9990) =     31.353 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 9.648 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.013 ms/op
Iteration   1: 3.654 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  22.609 ms/op
                 getUser·p0.9999: 24.510 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  24.908 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.500 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 36.494 ms/op
                 getUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270862
  mean =      3.543 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6076 
    [ 2.500,  5.000) = 255782 
    [ 5.000,  7.500) = 7029 
    [ 7.500, 10.000) = 1208 
    [10.000, 12.500) = 430 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.222 ms/op
     p(99.9900) =     35.640 ms/op
     p(99.9990) =     37.093 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 10.999 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.015 ms/op
Iteration   1: 4.175 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 24.250 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  15.339 ms/op
                 listUser·p0.9999: 22.811 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.114 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 17.014 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233814
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 218909 
    [ 5.000,  7.500) = 11573 
    [ 7.500, 10.000) = 2238 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.019 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     23.417 ms/op
     p(99.9990) =     25.502 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.078 ± 2.438  ops/ms
ClientPb.existUser                       thrpt       3   9.390 ± 0.573  ops/ms
ClientPb.getUser                         thrpt       3   8.943 ± 3.922  ops/ms
ClientPb.listUser                        thrpt       3   7.822 ± 3.179  ops/ms
ClientPb.createUser                       avgt       3   3.483 ± 1.031   ms/op
ClientPb.existUser                        avgt       3   3.360 ± 0.974   ms/op
ClientPb.getUser                          avgt       3   3.517 ± 1.275   ms/op
ClientPb.listUser                         avgt       3   4.176 ± 0.302   ms/op
ClientPb.createUser                     sample  267491   3.588 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.529           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.768           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  279335   3.437 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.534           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.432           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  270862   3.543 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.479           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.222           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  233814   4.102 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.019           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.417           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.083           ms/op
