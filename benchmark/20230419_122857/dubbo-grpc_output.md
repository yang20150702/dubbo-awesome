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
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 9.483 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 10.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.768 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (10.576, 10.768, 10.889), stdev = 0.168
  CI (99.9%): [7.701, 13.834] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.306 ops/ms
# Warmup Iteration   2: 10.958 ops/ms
# Warmup Iteration   3: 11.546 ops/ms
Iteration   1: 11.349 ops/ms
Iteration   2: 11.383 ops/ms
Iteration   3: 11.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.337 ±(99.9%) 0.972 ops/ms [Average]
  (min, avg, max) = (11.278, 11.337, 11.383), stdev = 0.053
  CI (99.9%): [10.365, 12.308] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.240 ops/ms
# Warmup Iteration   2: 10.580 ops/ms
# Warmup Iteration   3: 10.654 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.985 ops/ms
Iteration   3: 10.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.972 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (10.965, 10.972, 10.985), stdev = 0.011
  CI (99.9%): [10.763, 11.181] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.907 ops/ms
# Warmup Iteration   2: 8.264 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.576 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.512 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (8.394, 8.512, 8.576), stdev = 0.102
  CI (99.9%): [6.644, 10.379] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.009 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (2.987, 3.011, 3.052), stdev = 0.035
  CI (99.9%): [2.371, 3.652] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.857 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.830 ±(99.9%) 0.005 ms/op
Iteration   1: 2.785 ±(99.9%) 0.003 ms/op
Iteration   2: 2.784 ±(99.9%) 0.004 ms/op
Iteration   3: 2.792 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.787 ±(99.9%) 0.075 ms/op [Average]
  (min, avg, max) = (2.784, 2.787, 2.792), stdev = 0.004
  CI (99.9%): [2.712, 2.862] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.004 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.921 ±(99.9%) 0.055 ms/op [Average]
  (min, avg, max) = (2.919, 2.921, 2.925), stdev = 0.003
  CI (99.9%): [2.866, 2.976] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.049 ms/op
Iteration   1: 3.741 ±(99.9%) 0.024 ms/op
Iteration   2: 3.742 ±(99.9%) 0.030 ms/op
Iteration   3: 3.826 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.770 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.741, 3.770, 3.826), stdev = 0.049
  CI (99.9%): [2.879, 4.661] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.212 ms/op
                 createUser·p0.9999: 11.354 ms/op
                 createUser·p1.00:   11.747 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.791 ms/op
                 createUser·p0.9999: 13.456 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.818 ms/op
                 createUser·p0.9999: 20.032 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320338
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33483 
    [ 2.500,  5.000) = 285418 
    [ 5.000,  7.500) = 1159 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.045 ms/op
     p(99.9900) =     18.747 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.839 ±(99.9%) 0.006 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 17.338 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.831 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.016 ms/op
                 existUser·p0.9999: 13.539 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.895 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 23.886 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332537
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48837 
    [ 2.500,  5.000) = 282725 
    [ 5.000,  7.500) = 621 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.663 ms/op
     p(99.9900) =     17.555 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.844 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   4.093 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 12.126 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.102 ms/op
                 getUser·p0.9999: 21.503 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.260 ms/op
                 getUser·p0.9999: 16.614 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327099
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29229 
    [ 2.500,  5.000) = 296721 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.847 ms/op
     p(99.9900) =     18.047 ms/op
     p(99.9990) =     21.916 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.510 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 16.361 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.884 ms/op
                 listUser·p0.999:  14.006 ms/op
                 listUser·p0.9999: 15.516 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 22.193 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252840
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5618 
    [ 2.500,  5.000) = 228819 
    [ 5.000,  7.500) = 17134 
    [ 7.500, 10.000) = 710 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     21.486 ms/op
     p(99.9990) =     22.656 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.768 ± 3.067  ops/ms
ClientGrpc.existUser                       thrpt       3  11.337 ± 0.972  ops/ms
ClientGrpc.getUser                         thrpt       3  10.972 ± 0.209  ops/ms
ClientGrpc.listUser                        thrpt       3   8.512 ± 1.867  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.641   ms/op
ClientGrpc.existUser                        avgt       3   2.787 ± 0.075   ms/op
ClientGrpc.getUser                          avgt       3   2.921 ± 0.055   ms/op
ClientGrpc.listUser                         avgt       3   3.770 ± 0.891   ms/op
ClientGrpc.createUser                     sample  320338   2.997 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.045           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.747           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.120           ms/op
ClientGrpc.existUser                      sample  332537   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.663           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.555           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.183           ms/op
ClientGrpc.getUser                        sample  327099   2.933 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.478           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.363           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.047           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.086           ms/op
ClientGrpc.listUser                       sample  252840   3.797 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.893           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.221           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.486           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
