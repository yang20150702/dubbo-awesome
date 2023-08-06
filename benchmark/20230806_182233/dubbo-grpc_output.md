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
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 6.296 ops/ms
# Warmup Iteration   3: 7.779 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.181 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (8.041, 8.181, 8.267), stdev = 0.122
  CI (99.9%): [5.952, 10.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.813 ops/ms
# Warmup Iteration   2: 8.320 ops/ms
# Warmup Iteration   3: 8.896 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 9.015 ops/ms
Iteration   3: 9.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.042 ±(99.9%) 0.701 ops/ms [Average]
  (min, avg, max) = (9.015, 9.042, 9.086), stdev = 0.038
  CI (99.9%): [8.341, 9.743] (assumes normal distribution)


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
# Warmup Iteration   1: 5.540 ops/ms
# Warmup Iteration   2: 7.957 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.279 ops/ms
Iteration   2: 8.431 ops/ms
Iteration   3: 8.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.351 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (8.279, 8.351, 8.431), stdev = 0.076
  CI (99.9%): [6.962, 9.739] (assumes normal distribution)


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
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 5.762 ops/ms
# Warmup Iteration   3: 6.297 ops/ms
Iteration   1: 6.441 ops/ms
Iteration   2: 6.619 ops/ms
Iteration   3: 6.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.566 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (6.441, 6.566, 6.637), stdev = 0.109
  CI (99.9%): [4.584, 8.547] (assumes normal distribution)


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.007 ms/op
Iteration   1: 3.816 ±(99.9%) 0.004 ms/op
Iteration   2: 3.679 ±(99.9%) 0.004 ms/op
Iteration   3: 3.754 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.750 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.679, 3.750, 3.816), stdev = 0.068
  CI (99.9%): [2.500, 4.999] (assumes normal distribution)


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
# Warmup Iteration   1: 5.128 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.003 ms/op
Iteration   1: 3.564 ±(99.9%) 0.005 ms/op
Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
Iteration   3: 3.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.533 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.509, 3.533, 3.564), stdev = 0.028
  CI (99.9%): [3.024, 4.042] (assumes normal distribution)


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
# Warmup Iteration   1: 5.612 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.005 ms/op
Iteration   1: 3.835 ±(99.9%) 0.004 ms/op
Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
Iteration   3: 3.857 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.831 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.801, 3.831, 3.857), stdev = 0.029
  CI (99.9%): [3.310, 4.352] (assumes normal distribution)


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
# Warmup Iteration   1: 6.029 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.000 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.011 ms/op
Iteration   1: 4.647 ±(99.9%) 0.006 ms/op
Iteration   2: 4.819 ±(99.9%) 0.016 ms/op
Iteration   3: 4.759 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.742 ±(99.9%) 1.592 ms/op [Average]
  (min, avg, max) = (4.647, 4.742, 4.819), stdev = 0.087
  CI (99.9%): [3.150, 6.333] (assumes normal distribution)


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
# Warmup Iteration   1: 5.369 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.011 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  9.135 ms/op
                 createUser·p0.9999: 21.278 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.817 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  12.075 ms/op
                 createUser·p0.9999: 26.025 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 3.792 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  11.837 ms/op
                 createUser·p0.9999: 23.250 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254846
  mean =      3.769 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6309 
    [ 2.500,  5.000) = 237612 
    [ 5.000,  7.500) = 9449 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     25.626 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 5.269 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
Iteration   1: 3.601 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 20.353 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.586 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  10.285 ms/op
                 existUser·p0.9999: 20.876 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 3.617 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  12.451 ms/op
                 existUser·p0.9999: 33.040 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266476
  mean =      3.602 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11700 
    [ 2.500,  5.000) = 246008 
    [ 5.000,  7.500) = 7360 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     32.103 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.012 ms/op
Iteration   1: 3.651 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  9.349 ms/op
                 getUser·p0.9999: 24.624 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  11.854 ms/op
                 getUser·p0.9999: 27.174 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.726 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  9.209 ms/op
                 getUser·p0.9999: 30.048 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260780
  mean =      3.682 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8900 
    [ 2.500,  5.000) = 241883 
    [ 5.000,  7.500) = 8910 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =      9.834 ms/op
     p(99.9900) =     28.110 ms/op
     p(99.9990) =     30.504 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 6.014 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.318 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.017 ms/op
Iteration   1: 4.805 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  14.842 ms/op
                 listUser·p0.9999: 23.834 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.862 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.858 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  23.838 ms/op
                 listUser·p0.9999: 36.269 ms/op
                 listUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198192
  mean =      4.842 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 430 
    [ 2.500,  5.000) = 144213 
    [ 5.000,  7.500) = 46843 
    [ 7.500, 10.000) = 5714 
    [10.000, 12.500) = 577 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     34.072 ms/op
     p(99.9990) =     36.637 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.181 ± 2.229  ops/ms
ClientGrpc.existUser                       thrpt       3   9.042 ± 0.701  ops/ms
ClientGrpc.getUser                         thrpt       3   8.351 ± 1.389  ops/ms
ClientGrpc.listUser                        thrpt       3   6.566 ± 1.982  ops/ms
ClientGrpc.createUser                       avgt       3   3.750 ± 1.249   ms/op
ClientGrpc.existUser                        avgt       3   3.533 ± 0.509   ms/op
ClientGrpc.getUser                          avgt       3   3.831 ± 0.521   ms/op
ClientGrpc.listUser                         avgt       3   4.742 ± 1.592   ms/op
ClientGrpc.createUser                     sample  254846   3.769 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.814           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.611           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.403           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  266476   3.602 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.390           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.141           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.103           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.522           ms/op
ClientGrpc.getUser                        sample  260780   3.682 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.884           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.834           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.110           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.933           ms/op
ClientGrpc.listUser                       sample  198192   4.842 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.360           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.645           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.072           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.766           ms/op
