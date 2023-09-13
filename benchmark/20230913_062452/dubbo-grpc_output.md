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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 6.984 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 8.079 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.243 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (8.079, 8.243, 8.439), stdev = 0.182
  CI (99.9%): [4.916, 11.570] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.136 ops/ms
# Warmup Iteration   2: 8.130 ops/ms
# Warmup Iteration   3: 8.927 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 8.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.988 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (8.950, 8.988, 9.050), stdev = 0.054
  CI (99.9%): [8.000, 9.977] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.202 ops/ms
# Warmup Iteration   2: 8.022 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.397 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.551 ±(99.9%) 2.501 ops/ms [Average]
  (min, avg, max) = (8.397, 8.551, 8.662), stdev = 0.137
  CI (99.9%): [6.050, 11.051] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 6.117 ops/ms
Iteration   1: 6.494 ops/ms
Iteration   2: 6.569 ops/ms
Iteration   3: 6.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.547 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (6.494, 6.547, 6.576), stdev = 0.046
  CI (99.9%): [5.714, 7.380] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.303 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
Iteration   1: 3.887 ±(99.9%) 0.006 ms/op
Iteration   2: 3.817 ±(99.9%) 0.003 ms/op
Iteration   3: 3.845 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.849 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.817, 3.849, 3.887), stdev = 0.035
  CI (99.9%): [3.205, 4.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.870 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.003 ms/op
Iteration   1: 3.429 ±(99.9%) 0.005 ms/op
Iteration   2: 3.618 ±(99.9%) 0.003 ms/op
Iteration   3: 3.633 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.560 ±(99.9%) 2.078 ms/op [Average]
  (min, avg, max) = (3.429, 3.560, 3.633), stdev = 0.114
  CI (99.9%): [1.482, 5.638] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.290 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.003 ms/op
Iteration   1: 3.804 ±(99.9%) 0.005 ms/op
Iteration   2: 3.779 ±(99.9%) 0.003 ms/op
Iteration   3: 3.795 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.793 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.779, 3.793, 3.804), stdev = 0.012
  CI (99.9%): [3.568, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 7.079 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.019 ms/op
Iteration   1: 4.976 ±(99.9%) 0.012 ms/op
Iteration   2: 4.890 ±(99.9%) 0.012 ms/op
Iteration   3: 4.936 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.934 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (4.890, 4.934, 4.976), stdev = 0.043
  CI (99.9%): [4.153, 5.715] (assumes normal distribution)


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
# Warmup Iteration   1: 5.548 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.012 ms/op
Iteration   1: 3.847 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  14.499 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 3.768 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  9.881 ms/op
                 createUser·p0.9999: 25.871 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.819 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  11.571 ms/op
                 createUser·p0.9999: 37.593 ms/op
                 createUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251743
  mean =      3.811 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8713 
    [ 2.500,  5.000) = 228155 
    [ 5.000,  7.500) = 13023 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.935 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     37.267 ms/op
     p(99.9990) =     37.977 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.010 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  8.361 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 3.633 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  10.401 ms/op
                 existUser·p0.9999: 19.968 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 3.570 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 21.696 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267129
  mean =      3.594 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7129 
    [ 2.500,  5.000) = 251683 
    [ 5.000,  7.500) = 7340 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.064 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.526 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.009 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.594 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 22.660 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.810 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 17.865 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.825 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.665 ms/op
                 getUser·p0.999:  12.422 ms/op
                 getUser·p0.9999: 20.031 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249936
  mean =      3.838 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8310 
    [ 2.500,  5.000) = 225803 
    [ 5.000,  7.500) = 13635 
    [ 7.500, 10.000) = 1623 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.794 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.261 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.955 ±(99.9%) 0.016 ms/op
Iteration   1: 4.913 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  16.381 ms/op
                 listUser·p0.9999: 18.890 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 4.906 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.540 ms/op
                 listUser·p0.999:  18.017 ms/op
                 listUser·p0.9999: 21.132 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.974 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.276 ms/op
                 listUser·p0.999:  21.426 ms/op
                 listUser·p0.9999: 26.734 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194561
  mean =      4.931 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 133169 
    [ 5.000,  7.500) = 53019 
    [ 7.500, 10.000) = 6727 
    [10.000, 12.500) = 786 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     24.594 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.243 ± 3.327  ops/ms
ClientGrpc.existUser                       thrpt       3   8.988 ± 0.988  ops/ms
ClientGrpc.getUser                         thrpt       3   8.551 ± 2.501  ops/ms
ClientGrpc.listUser                        thrpt       3   6.547 ± 0.833  ops/ms
ClientGrpc.createUser                       avgt       3   3.849 ± 0.644   ms/op
ClientGrpc.existUser                        avgt       3   3.560 ± 2.078   ms/op
ClientGrpc.getUser                          avgt       3   3.793 ± 0.225   ms/op
ClientGrpc.listUser                         avgt       3   4.934 ± 0.781   ms/op
ClientGrpc.createUser                     sample  251743   3.811 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.788           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.935           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.207           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.267           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.191           ms/op
ClientGrpc.existUser                      sample  267129   3.594 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.898           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.152           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.732           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.037           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  249936   3.838 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.950           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.258           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.791           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  194561   4.931 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
