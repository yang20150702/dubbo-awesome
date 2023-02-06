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
# Warmup Iteration   1: 2.984 ops/ms
# Warmup Iteration   2: 6.846 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.659 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.469 ±(99.9%) 3.018 ops/ms [Average]
  (min, avg, max) = (8.360, 8.469, 8.659), stdev = 0.165
  CI (99.9%): [5.451, 11.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.952 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 8.982 ops/ms
Iteration   2: 8.665 ops/ms
Iteration   3: 8.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.796 ±(99.9%) 3.012 ops/ms [Average]
  (min, avg, max) = (8.665, 8.796, 8.982), stdev = 0.165
  CI (99.9%): [5.784, 11.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.413 ops/ms
# Warmup Iteration   2: 8.311 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.535 ops/ms
Iteration   2: 8.451 ops/ms
Iteration   3: 8.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.475 ±(99.9%) 0.956 ops/ms [Average]
  (min, avg, max) = (8.438, 8.475, 8.535), stdev = 0.052
  CI (99.9%): [7.518, 9.431] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ops/ms
# Warmup Iteration   2: 6.205 ops/ms
# Warmup Iteration   3: 6.772 ops/ms
Iteration   1: 6.739 ops/ms
Iteration   2: 6.739 ops/ms
Iteration   3: 6.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.719 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (6.678, 6.719, 6.739), stdev = 0.035
  CI (99.9%): [6.075, 7.363] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.522 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.012 ms/op
Iteration   1: 3.956 ±(99.9%) 0.002 ms/op
Iteration   2: 3.825 ±(99.9%) 0.003 ms/op
Iteration   3: 3.797 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.859 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (3.797, 3.859, 3.956), stdev = 0.085
  CI (99.9%): [2.310, 5.408] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.003 ms/op
Iteration   1: 3.590 ±(99.9%) 0.002 ms/op
Iteration   2: 3.681 ±(99.9%) 0.002 ms/op
Iteration   3: 3.687 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.653 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.590, 3.653, 3.687), stdev = 0.054
  CI (99.9%): [2.662, 4.643] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.009 ms/op
Iteration   1: 3.825 ±(99.9%) 0.002 ms/op
Iteration   2: 3.792 ±(99.9%) 0.004 ms/op
Iteration   3: 3.892 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.836 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.792, 3.836, 3.892), stdev = 0.051
  CI (99.9%): [2.909, 4.763] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.694 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.017 ms/op
Iteration   1: 4.874 ±(99.9%) 0.015 ms/op
Iteration   2: 4.833 ±(99.9%) 0.010 ms/op
Iteration   3: 4.813 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.840 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (4.813, 4.840, 4.874), stdev = 0.031
  CI (99.9%): [4.271, 5.409] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.468 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.010 ms/op
Iteration   1: 3.789 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  9.461 ms/op
                 createUser·p0.9999: 24.317 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   5.570 ms/op
                 createUser·p0.999:  10.187 ms/op
                 createUser·p0.9999: 22.091 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.761 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  9.910 ms/op
                 createUser·p0.9999: 25.001 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253893
  mean =      3.785 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7177 
    [ 2.500,  5.000) = 238445 
    [ 5.000,  7.500) = 7625 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.705 ms/op
     p(99.9900) =     24.629 ms/op
     p(99.9990) =     26.212 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.244 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.009 ms/op
Iteration   1: 3.746 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.544 ms/op
                 existUser·p0.9999: 15.669 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   2: 3.619 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 18.224 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 3.740 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259520
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 8222 
    [ 2.500,  3.750) = 137732 
    [ 3.750,  5.000) = 106416 
    [ 5.000,  6.250) = 5563 
    [ 6.250,  7.500) = 668 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.544 ms/op
     p(99.9000) =     11.247 ms/op
     p(99.9900) =     18.417 ms/op
     p(99.9990) =     19.458 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.010 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 14.905 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  13.362 ms/op
                 getUser·p0.9999: 16.073 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   3: 3.836 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  8.033 ms/op
                 getUser·p0.9999: 19.846 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248277
  mean =      3.866 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 6064 
    [ 2.500,  3.750) = 109702 
    [ 3.750,  5.000) = 120179 
    [ 5.000,  6.250) = 10403 
    [ 6.250,  7.500) = 996 
    [ 7.500,  8.750) = 423 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     10.313 ms/op
     p(99.9900) =     18.962 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 6.844 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.879 ±(99.9%) 0.014 ms/op
Iteration   1: 4.842 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  17.809 ms/op
                 listUser·p0.9999: 21.949 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 4.806 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  17.025 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.786 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  17.913 ms/op
                 listUser·p0.9999: 25.963 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199786
  mean =      4.811 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 145239 
    [ 5.000,  7.500) = 49205 
    [ 7.500, 10.000) = 4574 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.808 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     25.496 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.469 ± 3.018  ops/ms
ClientGrpc.existUser                       thrpt       3   8.796 ± 3.012  ops/ms
ClientGrpc.getUser                         thrpt       3   8.475 ± 0.956  ops/ms
ClientGrpc.listUser                        thrpt       3   6.719 ± 0.644  ops/ms
ClientGrpc.createUser                       avgt       3   3.859 ± 1.549   ms/op
ClientGrpc.existUser                        avgt       3   3.653 ± 0.991   ms/op
ClientGrpc.getUser                          avgt       3   3.836 ± 0.927   ms/op
ClientGrpc.listUser                         avgt       3   4.840 ± 0.569   ms/op
ClientGrpc.createUser                     sample  253893   3.785 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.506           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.705           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  259520   3.701 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.911           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.544           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.247           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.562           ms/op
ClientGrpc.getUser                        sample  248277   3.866 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.912           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.313           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.962           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  199786   4.811 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.496           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.017           ms/op
