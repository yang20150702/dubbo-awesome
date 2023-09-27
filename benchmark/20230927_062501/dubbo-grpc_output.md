# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 6.204 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.351 ops/ms
Iteration   2: 8.689 ops/ms
Iteration   3: 8.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.514 ±(99.9%) 3.089 ops/ms [Average]
  (min, avg, max) = (8.351, 8.514, 8.689), stdev = 0.169
  CI (99.9%): [5.425, 11.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.615 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 8.944 ops/ms
Iteration   2: 9.124 ops/ms
Iteration   3: 8.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.020 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (8.944, 9.020, 9.124), stdev = 0.093
  CI (99.9%): [7.323, 10.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ops/ms
# Warmup Iteration   2: 7.870 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 8.478 ops/ms
Iteration   2: 8.703 ops/ms
Iteration   3: 8.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.717 ±(99.9%) 4.501 ops/ms [Average]
  (min, avg, max) = (8.478, 8.717, 8.971), stdev = 0.247
  CI (99.9%): [4.217, 13.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 6.732 ops/ms
Iteration   1: 6.597 ops/ms
Iteration   2: 6.968 ops/ms
Iteration   3: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.852 ±(99.9%) 4.041 ops/ms [Average]
  (min, avg, max) = (6.597, 6.852, 6.992), stdev = 0.221
  CI (99.9%): [2.811, 10.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.562 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.008 ms/op
Iteration   1: 3.736 ±(99.9%) 0.006 ms/op
Iteration   2: 3.801 ±(99.9%) 0.015 ms/op
Iteration   3: 3.669 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.735 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (3.669, 3.735, 3.801), stdev = 0.066
  CI (99.9%): [2.532, 4.939] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.937 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.003 ms/op
Iteration   1: 3.463 ±(99.9%) 0.003 ms/op
Iteration   2: 3.421 ±(99.9%) 0.003 ms/op
Iteration   3: 3.382 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.422 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.382, 3.422, 3.463), stdev = 0.040
  CI (99.9%): [2.685, 4.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.003 ms/op
Iteration   1: 3.550 ±(99.9%) 0.005 ms/op
Iteration   2: 3.775 ±(99.9%) 0.004 ms/op
Iteration   3: 3.731 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.685 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (3.550, 3.685, 3.775), stdev = 0.119
  CI (99.9%): [1.514, 5.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.363 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.970 ±(99.9%) 0.015 ms/op
Iteration   1: 4.813 ±(99.9%) 0.014 ms/op
Iteration   2: 4.799 ±(99.9%) 0.017 ms/op
Iteration   3: 4.782 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.798 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (4.782, 4.798, 4.813), stdev = 0.016
  CI (99.9%): [4.510, 5.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.669 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.013 ms/op
Iteration   1: 3.687 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 23.713 ms/op
                 createUser·p1.00:   32.375 ms/op

Iteration   2: 3.676 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  12.072 ms/op
                 createUser·p0.9999: 28.059 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 3.652 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.041 ms/op
                 createUser·p0.999:  14.165 ms/op
                 createUser·p0.9999: 27.877 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261412
  mean =      3.672 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11766 
    [ 2.500,  5.000) = 238308 
    [ 5.000,  7.500) = 9372 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     27.815 ms/op
     p(99.9990) =     30.434 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.873 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.009 ms/op
Iteration   1: 3.456 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  8.773 ms/op
                 existUser·p0.9999: 15.892 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 3.471 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.935 ms/op
                 existUser·p0.999:  12.515 ms/op
                 existUser·p0.9999: 16.098 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 20.965 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275067
  mean =      3.488 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10436 
    [ 2.500,  5.000) = 256934 
    [ 5.000,  7.500) = 6262 
    [ 7.500, 10.000) = 896 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     12.516 ms/op
     p(99.9900) =     19.152 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.517 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.010 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  12.626 ms/op
                 getUser·p0.9999: 20.073 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.718 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 17.380 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.673 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.908 ms/op
                 getUser·p0.999:  11.755 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257274
  mean =      3.730 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9159 
    [ 2.500,  5.000) = 236631 
    [ 5.000,  7.500) = 9690 
    [ 7.500, 10.000) = 1357 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     11.645 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.224 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.942 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.754 ±(99.9%) 0.017 ms/op
Iteration   1: 4.871 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 22.952 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 4.714 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.228 ms/op
                 listUser·p0.9999: 21.121 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 4.913 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.390 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   10.204 ms/op
                 listUser·p0.999:  25.773 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198729
  mean =      4.831 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 757 
    [ 2.500,  5.000) = 144241 
    [ 5.000,  7.500) = 44589 
    [ 7.500, 10.000) = 7314 
    [10.000, 12.500) = 1111 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     28.873 ms/op
     p(99.9990) =     31.120 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.514 ± 3.089  ops/ms
ClientGrpc.existUser                       thrpt       3   9.020 ± 1.697  ops/ms
ClientGrpc.getUser                         thrpt       3   8.717 ± 4.501  ops/ms
ClientGrpc.listUser                        thrpt       3   6.852 ± 4.041  ops/ms
ClientGrpc.createUser                       avgt       3   3.735 ± 1.203   ms/op
ClientGrpc.existUser                        avgt       3   3.422 ± 0.737   ms/op
ClientGrpc.getUser                          avgt       3   3.685 ± 2.171   ms/op
ClientGrpc.listUser                         avgt       3   4.798 ± 0.288   ms/op
ClientGrpc.createUser                     sample  261412   3.672 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.037           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.484           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.815           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.375           ms/op
ClientGrpc.existUser                      sample  275067   3.488 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.738           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.357           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.516           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.152           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  257274   3.730 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.775           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.645           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.691           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  198729   4.831 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.390           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.973           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.873           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.932           ms/op
