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
# Warmup Iteration   1: 3.311 ops/ms
# Warmup Iteration   2: 6.812 ops/ms
# Warmup Iteration   3: 8.257 ops/ms
Iteration   1: 8.602 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.491 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (8.395, 8.491, 8.602), stdev = 0.105
  CI (99.9%): [6.583, 10.399] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.096 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 8.704 ops/ms
Iteration   1: 9.004 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 9.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.983 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (8.844, 8.983, 9.099), stdev = 0.129
  CI (99.9%): [6.626, 11.339] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ops/ms
# Warmup Iteration   2: 8.185 ops/ms
# Warmup Iteration   3: 8.659 ops/ms
Iteration   1: 8.488 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.609 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (8.488, 8.609, 8.722), stdev = 0.117
  CI (99.9%): [6.467, 10.751] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.525 ops/ms
# Warmup Iteration   2: 6.509 ops/ms
# Warmup Iteration   3: 6.896 ops/ms
Iteration   1: 6.882 ops/ms
Iteration   2: 6.909 ops/ms
Iteration   3: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.927 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (6.882, 6.927, 6.992), stdev = 0.057
  CI (99.9%): [5.883, 7.972] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.587 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.004 ms/op
Iteration   1: 3.811 ±(99.9%) 0.003 ms/op
Iteration   2: 3.763 ±(99.9%) 0.004 ms/op
Iteration   3: 3.877 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.817 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.763, 3.817, 3.877), stdev = 0.058
  CI (99.9%): [2.767, 4.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.002 ms/op
Iteration   1: 3.499 ±(99.9%) 0.003 ms/op
Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.538 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.499, 3.538, 3.577), stdev = 0.039
  CI (99.9%): [2.826, 4.250] (assumes normal distribution)


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
# Warmup Iteration   1: 4.989 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.006 ms/op
Iteration   1: 3.756 ±(99.9%) 0.004 ms/op
Iteration   2: 3.753 ±(99.9%) 0.003 ms/op
Iteration   3: 3.808 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.772 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.753, 3.772, 3.808), stdev = 0.031
  CI (99.9%): [3.213, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 7.512 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.022 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.007 ms/op
Iteration   1: 4.863 ±(99.9%) 0.029 ms/op
Iteration   2: 4.748 ±(99.9%) 0.023 ms/op
Iteration   3: 4.705 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.772 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (4.705, 4.772, 4.863), stdev = 0.081
  CI (99.9%): [3.290, 6.254] (assumes normal distribution)


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
# Warmup Iteration   1: 5.317 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.009 ms/op
Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  9.786 ms/op
                 createUser·p0.9999: 14.524 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 3.861 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 15.687 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  12.066 ms/op
                 createUser·p0.9999: 20.558 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251284
  mean =      3.820 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7592 
    [ 2.500,  5.000) = 232720 
    [ 5.000,  7.500) = 10347 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.477 ms/op
     p(99.9900) =     19.910 ms/op
     p(99.9990) =     20.987 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 5.102 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.009 ms/op
Iteration   1: 3.688 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.299 ms/op
                 existUser·p0.999:  9.294 ms/op
                 existUser·p0.9999: 14.800 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.568 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  7.260 ms/op
                 existUser·p0.9999: 15.796 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 21.118 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264132
  mean =      3.634 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7490 
    [ 2.500,  5.000) = 252899 
    [ 5.000,  7.500) = 3191 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      9.238 ms/op
     p(99.9900) =     20.794 ms/op
     p(99.9990) =     21.487 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 5.481 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
Iteration   1: 3.803 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  12.292 ms/op
                 getUser·p0.9999: 16.689 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 3.735 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  9.227 ms/op
                 getUser·p0.9999: 19.347 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  7.835 ms/op
                 getUser·p0.9999: 20.171 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254336
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6455 
    [ 2.500,  5.000) = 239599 
    [ 5.000,  7.500) = 7525 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     20.444 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 6.630 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.671 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.015 ms/op
Iteration   1: 4.859 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 20.995 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.772 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  17.463 ms/op
                 listUser·p0.9999: 19.533 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   3: 4.716 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  19.768 ms/op
                 listUser·p0.9999: 33.765 ms/op
                 listUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200748
  mean =      4.782 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 146309 
    [ 5.000,  7.500) = 49315 
    [ 7.500, 10.000) = 4097 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     32.622 ms/op
     p(99.9990) =     34.274 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.491 ± 1.908  ops/ms
ClientGrpc.existUser                       thrpt       3   8.983 ± 2.356  ops/ms
ClientGrpc.getUser                         thrpt       3   8.609 ± 2.142  ops/ms
ClientGrpc.listUser                        thrpt       3   6.927 ± 1.044  ops/ms
ClientGrpc.createUser                       avgt       3   3.817 ± 1.050   ms/op
ClientGrpc.existUser                        avgt       3   3.538 ± 0.712   ms/op
ClientGrpc.getUser                          avgt       3   3.772 ± 0.559   ms/op
ClientGrpc.listUser                         avgt       3   4.772 ± 1.482   ms/op
ClientGrpc.createUser                     sample  251284   3.820 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.527           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.477           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.910           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.103           ms/op
ClientGrpc.existUser                      sample  264132   3.634 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.238           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.794           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  254336   3.775 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.638           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.125           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.431           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  200748   4.782 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.252           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.622           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.406           ms/op
