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
# Warmup Iteration   1: 3.065 ops/ms
# Warmup Iteration   2: 6.857 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.513 ops/ms
Iteration   2: 8.598 ops/ms
Iteration   3: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.610 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (8.513, 8.610, 8.719), stdev = 0.103
  CI (99.9%): [6.722, 10.498] (assumes normal distribution)


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
# Warmup Iteration   1: 5.897 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 9.086 ops/ms
Iteration   2: 9.192 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.271 ±(99.9%) 4.296 ops/ms [Average]
  (min, avg, max) = (9.086, 9.271, 9.536), stdev = 0.235
  CI (99.9%): [4.975, 13.567] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.758 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.470 ops/ms
Iteration   1: 8.522 ops/ms
Iteration   2: 8.589 ops/ms
Iteration   3: 8.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.500 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (8.390, 8.500, 8.589), stdev = 0.101
  CI (99.9%): [6.658, 10.342] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 5.965 ops/ms
# Warmup Iteration   3: 6.640 ops/ms
Iteration   1: 6.595 ops/ms
Iteration   2: 6.603 ops/ms
Iteration   3: 6.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.609 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (6.595, 6.609, 6.631), stdev = 0.019
  CI (99.9%): [6.269, 6.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.014 ms/op
Iteration   1: 3.809 ±(99.9%) 0.004 ms/op
Iteration   2: 3.710 ±(99.9%) 0.003 ms/op
Iteration   3: 3.776 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.765 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.710, 3.765, 3.809), stdev = 0.050
  CI (99.9%): [2.844, 4.686] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.102 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.004 ms/op
Iteration   1: 3.675 ±(99.9%) 0.004 ms/op
Iteration   2: 3.464 ±(99.9%) 0.002 ms/op
Iteration   3: 3.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.535 ±(99.9%) 2.210 ms/op [Average]
  (min, avg, max) = (3.464, 3.535, 3.675), stdev = 0.121
  CI (99.9%): [1.325, 5.745] (assumes normal distribution)


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
Iteration   1: 3.697 ±(99.9%) 0.003 ms/op
Iteration   2: 3.682 ±(99.9%) 0.004 ms/op
Iteration   3: 3.695 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.691 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.682, 3.691, 3.697), stdev = 0.009
  CI (99.9%): [3.534, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 6.517 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.910 ±(99.9%) 0.024 ms/op
Iteration   1: 5.037 ±(99.9%) 0.020 ms/op
Iteration   2: 5.004 ±(99.9%) 0.022 ms/op
Iteration   3: 4.882 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.974 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (4.882, 4.974, 5.037), stdev = 0.081
  CI (99.9%): [3.491, 6.458] (assumes normal distribution)


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
# Warmup Iteration   1: 5.466 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.010 ms/op
Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.707 ms/op
                 createUser·p0.999:  11.940 ms/op
                 createUser·p0.9999: 15.948 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   2: 3.643 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  14.670 ms/op
                 createUser·p0.9999: 16.905 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.723 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.677 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260159
  mean =      3.691 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6421 
    [ 2.500,  5.000) = 244028 
    [ 5.000,  7.500) = 8259 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     11.480 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     21.469 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.009 ms/op
Iteration   1: 3.582 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.579 ms/op
                 existUser·p0.9999: 16.598 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 3.500 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  9.530 ms/op
                 existUser·p0.9999: 30.961 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 23.113 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272694
  mean =      3.519 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11812 
    [ 2.500,  5.000) = 252168 
    [ 5.000,  7.500) = 7222 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     29.647 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 5.676 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.010 ms/op
Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  11.369 ms/op
                 getUser·p0.9999: 16.244 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 3.680 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 18.645 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.701 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  10.620 ms/op
                 getUser·p0.9999: 18.690 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258447
  mean =      3.714 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4508 
    [ 2.500,  5.000) = 244573 
    [ 5.000,  7.500) = 8095 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     10.020 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     20.704 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 6.919 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.938 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.889 ±(99.9%) 0.016 ms/op
Iteration   1: 4.906 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  15.413 ms/op
                 listUser·p0.9999: 18.296 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 4.804 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  17.938 ms/op
                 listUser·p0.9999: 24.522 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.788 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  20.485 ms/op
                 listUser·p0.9999: 23.488 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198624
  mean =      4.832 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 346 
    [ 2.500,  5.000) = 143727 
    [ 5.000,  7.500) = 47762 
    [ 7.500, 10.000) = 5773 
    [10.000, 12.500) = 621 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     24.286 ms/op
     p(99.9990) =     26.117 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.610 ± 1.888  ops/ms
ClientGrpc.existUser                       thrpt       3   9.271 ± 4.296  ops/ms
ClientGrpc.getUser                         thrpt       3   8.500 ± 1.842  ops/ms
ClientGrpc.listUser                        thrpt       3   6.609 ± 0.340  ops/ms
ClientGrpc.createUser                       avgt       3   3.765 ± 0.921   ms/op
ClientGrpc.existUser                        avgt       3   3.535 ± 2.210   ms/op
ClientGrpc.getUser                          avgt       3   3.691 ± 0.157   ms/op
ClientGrpc.listUser                         avgt       3   4.974 ± 1.483   ms/op
ClientGrpc.createUser                     sample  260159   3.691 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.513           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.480           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.890           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  272694   3.519 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.774           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.647           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.326           ms/op
ClientGrpc.getUser                        sample  258447   3.714 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.725           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.020           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.612           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  198624   4.832 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.613           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
