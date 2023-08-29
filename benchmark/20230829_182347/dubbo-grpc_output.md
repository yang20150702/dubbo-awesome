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
# Warmup Iteration   1: 3.127 ops/ms
# Warmup Iteration   2: 6.828 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 8.351 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.418 ±(99.9%) 2.211 ops/ms [Average]
  (min, avg, max) = (8.345, 8.418, 8.558), stdev = 0.121
  CI (99.9%): [6.207, 10.628] (assumes normal distribution)


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
# Warmup Iteration   2: 8.432 ops/ms
# Warmup Iteration   3: 8.920 ops/ms
Iteration   1: 9.213 ops/ms
Iteration   2: 8.977 ops/ms
Iteration   3: 9.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.080 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (8.977, 9.080, 9.213), stdev = 0.121
  CI (99.9%): [6.873, 11.287] (assumes normal distribution)


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
# Warmup Iteration   1: 5.390 ops/ms
# Warmup Iteration   2: 8.039 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.514 ops/ms
Iteration   2: 8.583 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.469 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (8.308, 8.469, 8.583), stdev = 0.143
  CI (99.9%): [5.855, 11.082] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.317 ops/ms
# Warmup Iteration   2: 6.209 ops/ms
# Warmup Iteration   3: 6.592 ops/ms
Iteration   1: 6.607 ops/ms
Iteration   2: 6.580 ops/ms
Iteration   3: 6.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.564 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (6.505, 6.564, 6.607), stdev = 0.053
  CI (99.9%): [5.606, 7.522] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.651 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.007 ms/op
Iteration   1: 3.859 ±(99.9%) 0.003 ms/op
Iteration   2: 3.773 ±(99.9%) 0.002 ms/op
Iteration   3: 3.758 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.797 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (3.758, 3.797, 3.859), stdev = 0.055
  CI (99.9%): [2.793, 4.800] (assumes normal distribution)


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.003 ms/op
Iteration   1: 3.480 ±(99.9%) 0.003 ms/op
Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
Iteration   3: 3.598 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.538 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.480, 3.538, 3.598), stdev = 0.059
  CI (99.9%): [2.457, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.002 ms/op
Iteration   1: 3.875 ±(99.9%) 0.006 ms/op
Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
Iteration   3: 3.819 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.791 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (3.678, 3.791, 3.875), stdev = 0.101
  CI (99.9%): [1.940, 5.642] (assumes normal distribution)


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
# Warmup Iteration   1: 7.093 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.192 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.015 ms/op
Iteration   1: 4.864 ±(99.9%) 0.015 ms/op
Iteration   2: 4.816 ±(99.9%) 0.011 ms/op
Iteration   3: 4.805 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.828 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (4.805, 4.828, 4.864), stdev = 0.032
  CI (99.9%): [4.251, 5.406] (assumes normal distribution)


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
# Warmup Iteration   1: 5.681 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.010 ms/op
Iteration   1: 3.753 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   5.970 ms/op
                 createUser·p0.999:  10.535 ms/op
                 createUser·p0.9999: 17.121 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  12.618 ms/op
                 createUser·p0.9999: 21.976 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  14.978 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255086
  mean =      3.764 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5176 
    [ 2.500,  5.000) = 241658 
    [ 5.000,  7.500) = 7257 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     11.843 ms/op
     p(99.9900) =     24.034 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
Iteration   1: 3.707 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  8.888 ms/op
                 existUser·p0.9999: 14.840 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 3.646 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.729 ms/op
                 existUser·p0.9999: 15.995 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 3.604 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 19.505 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262721
  mean =      3.652 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 6134 
    [ 2.500,  3.750) = 164518 
    [ 3.750,  5.000) = 85996 
    [ 5.000,  6.250) = 4179 
    [ 6.250,  7.500) = 640 
    [ 7.500,  8.750) = 488 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     17.013 ms/op
     p(99.9990) =     19.784 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 5.380 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.012 ms/op
Iteration   1: 3.786 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 15.394 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 3.781 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  10.757 ms/op
                 getUser·p0.9999: 16.828 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.750 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  8.827 ms/op
                 getUser·p0.9999: 18.938 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254384
  mean =      3.772 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 6650 
    [ 2.500,  3.750) = 128886 
    [ 3.750,  5.000) = 109584 
    [ 5.000,  6.250) = 7092 
    [ 6.250,  7.500) = 1043 
    [ 7.500,  8.750) = 607 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =      9.988 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     19.283 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 7.061 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.918 ±(99.9%) 0.018 ms/op
Iteration   1: 4.825 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  26.202 ms/op
                 listUser·p0.9999: 29.122 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 4.832 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 27.615 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 4.904 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  22.491 ms/op
                 listUser·p0.9999: 25.378 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197804
  mean =      4.853 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 142364 
    [ 5.000,  7.500) = 48567 
    [ 7.500, 10.000) = 5653 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     24.084 ms/op
     p(99.9900) =     28.399 ms/op
     p(99.9990) =     29.296 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.418 ± 2.211  ops/ms
ClientGrpc.existUser                       thrpt       3   9.080 ± 2.207  ops/ms
ClientGrpc.getUser                         thrpt       3   8.469 ± 2.613  ops/ms
ClientGrpc.listUser                        thrpt       3   6.564 ± 0.958  ops/ms
ClientGrpc.createUser                       avgt       3   3.797 ± 1.003   ms/op
ClientGrpc.existUser                        avgt       3   3.538 ± 1.082   ms/op
ClientGrpc.getUser                          avgt       3   3.791 ± 1.851   ms/op
ClientGrpc.listUser                         avgt       3   4.828 ± 0.577   ms/op
ClientGrpc.createUser                     sample  255086   3.764 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.783           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.843           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.034           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  262721   3.652 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.810           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.013           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  254384   3.772 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.922           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.138           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  197804   4.853 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.264           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.084           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.399           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.360           ms/op
