# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.058 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 6.546 ops/ms
Iteration   1: 7.030 ops/ms
Iteration   2: 7.102 ops/ms
Iteration   3: 7.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.076 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (7.030, 7.076, 7.102), stdev = 0.040
  CI (99.9%): [6.344, 7.809] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ops/ms
# Warmup Iteration   2: 6.908 ops/ms
# Warmup Iteration   3: 7.121 ops/ms
Iteration   1: 7.345 ops/ms
Iteration   2: 7.267 ops/ms
Iteration   3: 7.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.331 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (7.267, 7.331, 7.381), stdev = 0.058
  CI (99.9%): [6.271, 8.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ops/ms
# Warmup Iteration   2: 6.327 ops/ms
# Warmup Iteration   3: 6.606 ops/ms
Iteration   1: 7.026 ops/ms
Iteration   2: 7.009 ops/ms
Iteration   3: 7.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.055 ±(99.9%) 1.189 ops/ms [Average]
  (min, avg, max) = (7.009, 7.055, 7.130), stdev = 0.065
  CI (99.9%): [5.866, 8.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 4.899 ops/ms
# Warmup Iteration   3: 5.442 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.368 ops/ms
Iteration   3: 5.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.431 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (5.368, 5.431, 5.469), stdev = 0.055
  CI (99.9%): [4.433, 6.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.404 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.012 ms/op
Iteration   1: 4.454 ±(99.9%) 0.005 ms/op
Iteration   2: 4.502 ±(99.9%) 0.005 ms/op
Iteration   3: 4.242 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.399 ±(99.9%) 2.522 ms/op [Average]
  (min, avg, max) = (4.242, 4.399, 4.502), stdev = 0.138
  CI (99.9%): [1.877, 6.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.860 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.006 ms/op
Iteration   1: 4.249 ±(99.9%) 0.003 ms/op
Iteration   2: 4.329 ±(99.9%) 0.004 ms/op
Iteration   3: 4.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.334 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (4.249, 4.334, 4.425), stdev = 0.088
  CI (99.9%): [2.727, 5.942] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.498 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.583 ±(99.9%) 0.005 ms/op
Iteration   1: 4.445 ±(99.9%) 0.004 ms/op
Iteration   2: 4.487 ±(99.9%) 0.004 ms/op
Iteration   3: 4.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.466 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (4.445, 4.466, 4.487), stdev = 0.021
  CI (99.9%): [4.080, 4.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.874 ±(99.9%) 0.022 ms/op
Iteration   1: 5.950 ±(99.9%) 0.045 ms/op
Iteration   2: 5.826 ±(99.9%) 0.018 ms/op
Iteration   3: 5.738 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.838 ±(99.9%) 1.945 ms/op [Average]
  (min, avg, max) = (5.738, 5.838, 5.950), stdev = 0.107
  CI (99.9%): [3.892, 7.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.448 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.885 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.018 ms/op
Iteration   1: 4.669 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.988 ms/op
                 createUser·p0.95:   6.521 ms/op
                 createUser·p0.99:   8.143 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 27.124 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   8.449 ms/op
                 createUser·p0.999:  13.678 ms/op
                 createUser·p0.9999: 28.310 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 4.686 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  14.520 ms/op
                 createUser·p0.9999: 31.758 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 206874
  mean =      4.637 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3132 
    [ 2.500,  5.000) = 138210 
    [ 5.000,  7.500) = 61130 
    [ 7.500, 10.000) = 3743 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     13.453 ms/op
     p(99.9900) =     30.822 ms/op
     p(99.9990) =     32.073 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.564 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.013 ms/op
Iteration   1: 4.331 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   4.186 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  12.459 ms/op
                 existUser·p0.9999: 19.537 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 4.214 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  11.109 ms/op
                 existUser·p0.9999: 22.060 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  11.086 ms/op
                 existUser·p0.9999: 22.188 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229160
  mean =      4.187 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5025 
    [ 2.500,  5.000) = 189047 
    [ 5.000,  7.500) = 32076 
    [ 7.500, 10.000) = 2373 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     21.501 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.153 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.560 ±(99.9%) 0.015 ms/op
Iteration   1: 4.576 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  12.568 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 4.357 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  11.013 ms/op
                 getUser·p0.9999: 22.478 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 4.335 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  15.372 ms/op
                 getUser·p0.9999: 27.128 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217151
  mean =      4.420 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7854 
    [ 2.500,  5.000) = 157712 
    [ 5.000,  7.500) = 46803 
    [ 7.500, 10.000) = 3934 
    [10.000, 12.500) = 611 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     12.728 ms/op
     p(99.9900) =     26.430 ms/op
     p(99.9990) =     27.634 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.649 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.408 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.985 ±(99.9%) 0.027 ms/op
Iteration   1: 5.962 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 23.942 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 5.833 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.288 ms/op
                 listUser·p0.999:  22.616 ms/op
                 listUser·p0.9999: 25.510 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   3: 5.740 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 25.835 ms/op
                 listUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164154
  mean =      5.844 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 57019 
    [ 5.000,  7.500) = 83101 
    [ 7.500, 10.000) = 19231 
    [10.000, 12.500) = 3279 
    [12.500, 15.000) = 729 
    [15.000, 17.500) = 260 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      8.077 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     11.902 ms/op
     p(99.9000) =     20.442 ms/op
     p(99.9900) =     25.139 ms/op
     p(99.9990) =     30.214 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.076 ± 0.732  ops/ms
ClientGrpc.existUser                       thrpt       3   7.331 ± 1.060  ops/ms
ClientGrpc.getUser                         thrpt       3   7.055 ± 1.189  ops/ms
ClientGrpc.listUser                        thrpt       3   5.431 ± 0.997  ops/ms
ClientGrpc.createUser                       avgt       3   4.399 ± 2.522   ms/op
ClientGrpc.existUser                        avgt       3   4.334 ± 1.607   ms/op
ClientGrpc.getUser                          avgt       3   4.466 ± 0.386   ms/op
ClientGrpc.listUser                         avgt       3   5.838 ± 1.945   ms/op
ClientGrpc.createUser                     sample  206874   4.637 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.690           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.668           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.453           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.822           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.211           ms/op
ClientGrpc.existUser                      sample  229160   4.187 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.026           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.897           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.501           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  217151   4.420 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.800           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.496           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.728           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.115           ms/op
ClientGrpc.listUser                       sample  164154   5.844 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.902           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.442           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.139           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.325           ms/op
