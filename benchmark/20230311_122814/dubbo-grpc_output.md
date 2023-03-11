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
# Warmup Iteration   1: 2.505 ops/ms
# Warmup Iteration   2: 5.580 ops/ms
# Warmup Iteration   3: 7.239 ops/ms
Iteration   1: 7.750 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.845 ±(99.9%) 3.041 ops/ms [Average]
  (min, avg, max) = (7.747, 7.845, 8.037), stdev = 0.167
  CI (99.9%): [4.803, 10.886] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.428 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.325 ±(99.9%) 2.076 ops/ms [Average]
  (min, avg, max) = (8.203, 8.325, 8.428), stdev = 0.114
  CI (99.9%): [6.248, 10.401] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.990 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.200 ops/ms
Iteration   3: 8.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.230 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (8.155, 8.230, 8.337), stdev = 0.095
  CI (99.9%): [6.499, 9.961] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 5.584 ops/ms
# Warmup Iteration   3: 6.185 ops/ms
Iteration   1: 6.374 ops/ms
Iteration   2: 6.227 ops/ms
Iteration   3: 6.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.322 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (6.227, 6.322, 6.374), stdev = 0.082
  CI (99.9%): [4.824, 7.820] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.062 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.011 ms/op
Iteration   1: 3.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.875 ±(99.9%) 0.003 ms/op
Iteration   3: 3.822 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.895 ±(99.9%) 1.541 ms/op [Average]
  (min, avg, max) = (3.822, 3.895, 3.988), stdev = 0.084
  CI (99.9%): [2.354, 5.436] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.777 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.003 ms/op
Iteration   1: 3.677 ±(99.9%) 0.003 ms/op
Iteration   2: 3.632 ±(99.9%) 0.003 ms/op
Iteration   3: 3.727 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.678 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.632, 3.678, 3.727), stdev = 0.047
  CI (99.9%): [2.814, 4.543] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.212 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.003 ms/op
Iteration   1: 3.879 ±(99.9%) 0.005 ms/op
Iteration   2: 3.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.937 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.879, 3.937, 3.975), stdev = 0.051
  CI (99.9%): [3.010, 4.864] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.626 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.366 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.168 ±(99.9%) 0.019 ms/op
Iteration   1: 5.008 ±(99.9%) 0.015 ms/op
Iteration   2: 5.010 ±(99.9%) 0.018 ms/op
Iteration   3: 5.149 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.056 ±(99.9%) 1.475 ms/op [Average]
  (min, avg, max) = (5.008, 5.056, 5.149), stdev = 0.081
  CI (99.9%): [3.581, 6.531] (assumes normal distribution)


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
# Warmup Iteration   1: 6.358 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.014 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  13.817 ms/op
                 createUser·p0.9999: 17.392 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  13.167 ms/op
                 createUser·p0.9999: 18.848 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  14.113 ms/op
                 createUser·p0.9999: 20.345 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240709
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6894 
    [ 2.500,  5.000) = 210687 
    [ 5.000,  7.500) = 21345 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.423 ms/op
     p(99.9900) =     19.855 ms/op
     p(99.9990) =     20.571 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.548 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.010 ms/op
Iteration   1: 3.687 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  13.374 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.591 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.524 ms/op
                 existUser·p0.999:  10.337 ms/op
                 existUser·p0.9999: 17.665 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.661 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.563 ms/op
                 existUser·p0.999:  12.693 ms/op
                 existUser·p0.9999: 23.399 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263066
  mean =      3.646 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13848 
    [ 2.500,  5.000) = 237750 
    [ 5.000,  7.500) = 9472 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     26.063 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.955 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  13.009 ms/op
                 getUser·p0.9999: 19.988 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.844 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  13.411 ms/op
                 getUser·p0.9999: 17.684 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.792 ms/op
                 getUser·p0.999:  10.739 ms/op
                 getUser·p0.9999: 20.499 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247899
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9928 
    [ 2.500,  5.000) = 220726 
    [ 5.000,  7.500) = 15040 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     12.306 ms/op
     p(99.9900) =     20.192 ms/op
     p(99.9990) =     20.630 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.264 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.669 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.268 ±(99.9%) 0.020 ms/op
Iteration   1: 5.272 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  19.409 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 5.156 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.594 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  25.325 ms/op
                 listUser·p0.9999: 30.275 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   3: 5.138 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  20.698 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185155
  mean =      5.188 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 101213 
    [ 5.000,  7.500) = 71625 
    [ 7.500, 10.000) = 10008 
    [10.000, 12.500) = 1249 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     29.573 ms/op
     p(99.9990) =     30.746 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.845 ± 3.041  ops/ms
ClientGrpc.existUser                       thrpt       3   8.325 ± 2.076  ops/ms
ClientGrpc.getUser                         thrpt       3   8.230 ± 1.731  ops/ms
ClientGrpc.listUser                        thrpt       3   6.322 ± 1.498  ops/ms
ClientGrpc.createUser                       avgt       3   3.895 ± 1.541   ms/op
ClientGrpc.existUser                        avgt       3   3.678 ± 0.865   ms/op
ClientGrpc.getUser                          avgt       3   3.937 ± 0.927   ms/op
ClientGrpc.listUser                         avgt       3   5.056 ± 1.475   ms/op
ClientGrpc.createUser                     sample  240709   3.988 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.865           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.873           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.423           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.855           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  263066   3.646 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.920           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.288           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.461           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.116           ms/op
ClientGrpc.getUser                        sample  247899   3.872 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.235           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.192           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  185155   5.188 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.235           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.807           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.577           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
