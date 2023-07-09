# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 7.167 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.857 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.891 ±(99.9%) 3.694 ops/ms [Average]
  (min, avg, max) = (8.707, 8.891, 9.108), stdev = 0.203
  CI (99.9%): [5.196, 12.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.271 ops/ms
# Warmup Iteration   2: 8.837 ops/ms
# Warmup Iteration   3: 9.420 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.593 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.477 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (9.364, 9.477, 9.593), stdev = 0.114
  CI (99.9%): [7.392, 11.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.862 ops/ms
# Warmup Iteration   2: 8.397 ops/ms
# Warmup Iteration   3: 8.875 ops/ms
Iteration   1: 8.919 ops/ms
Iteration   2: 8.655 ops/ms
Iteration   3: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.817 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (8.655, 8.817, 8.919), stdev = 0.142
  CI (99.9%): [6.230, 11.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 6.285 ops/ms
# Warmup Iteration   3: 7.004 ops/ms
Iteration   1: 6.940 ops/ms
Iteration   2: 6.988 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.910 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (6.803, 6.910, 6.988), stdev = 0.096
  CI (99.9%): [5.159, 8.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.089 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.005 ms/op
Iteration   1: 3.728 ±(99.9%) 0.014 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.588 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.644 ±(99.9%) 1.351 ms/op [Average]
  (min, avg, max) = (3.588, 3.644, 3.728), stdev = 0.074
  CI (99.9%): [2.293, 4.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.887 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.006 ms/op
Iteration   1: 3.437 ±(99.9%) 0.003 ms/op
Iteration   2: 3.507 ±(99.9%) 0.002 ms/op
Iteration   3: 3.373 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.439 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.373, 3.439, 3.507), stdev = 0.067
  CI (99.9%): [2.219, 4.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.004 ms/op
Iteration   1: 3.493 ±(99.9%) 0.004 ms/op
Iteration   2: 3.566 ±(99.9%) 0.011 ms/op
Iteration   3: 3.589 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.549 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.493, 3.549, 3.589), stdev = 0.050
  CI (99.9%): [2.642, 4.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.865 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.012 ms/op
Iteration   1: 4.556 ±(99.9%) 0.016 ms/op
Iteration   2: 4.658 ±(99.9%) 0.029 ms/op
Iteration   3: 4.532 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.582 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (4.532, 4.582, 4.658), stdev = 0.067
  CI (99.9%): [3.364, 5.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.007 ms/op
Iteration   1: 3.606 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 18.387 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.517 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  12.733 ms/op
                 createUser·p0.9999: 14.516 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.586 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  11.385 ms/op
                 createUser·p0.9999: 18.632 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268919
  mean =      3.569 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5997 
    [ 2.500,  5.000) = 259183 
    [ 5.000,  7.500) = 3208 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.257 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.008 ms/op
Iteration   1: 3.372 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  7.128 ms/op
                 existUser·p0.9999: 16.425 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   2: 3.450 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 15.977 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   3: 3.454 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  8.675 ms/op
                 existUser·p0.9999: 19.685 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280228
  mean =      3.425 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10092 
    [ 2.500,  5.000) = 267085 
    [ 5.000,  7.500) = 2656 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.008 ms/op
Iteration   1: 3.604 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  7.973 ms/op
                 getUser·p0.9999: 19.570 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.614 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 15.130 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 3.567 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  8.772 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267001
  mean =      3.595 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8351 
    [ 2.500,  5.000) = 252951 
    [ 5.000,  7.500) = 5143 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     21.440 ms/op
     p(99.9990) =     21.965 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.934 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.892 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.013 ms/op
Iteration   1: 4.652 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  14.539 ms/op
                 listUser·p0.9999: 21.631 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 4.625 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  16.248 ms/op
                 listUser·p0.9999: 18.260 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.666 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.247 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 25.583 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206541
  mean =      4.648 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 170496 
    [ 5.000,  7.500) = 31689 
    [ 7.500, 10.000) = 3505 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     16.260 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     26.568 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.891 ± 3.694  ops/ms
ClientGrpc.existUser                       thrpt       3   9.477 ± 2.086  ops/ms
ClientGrpc.getUser                         thrpt       3   8.817 ± 2.587  ops/ms
ClientGrpc.listUser                        thrpt       3   6.910 ± 1.751  ops/ms
ClientGrpc.createUser                       avgt       3   3.644 ± 1.351   ms/op
ClientGrpc.existUser                        avgt       3   3.439 ± 1.220   ms/op
ClientGrpc.getUser                          avgt       3   3.549 ± 0.907   ms/op
ClientGrpc.listUser                         avgt       3   4.582 ± 1.218   ms/op
ClientGrpc.createUser                     sample  268919   3.569 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.932           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.350           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  280228   3.425 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.095           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.578           ms/op
ClientGrpc.getUser                        sample  267001   3.595 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.440           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  206541   4.648 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.260           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
