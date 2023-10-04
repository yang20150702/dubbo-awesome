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
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 7.366 ops/ms
Iteration   1: 7.459 ops/ms
Iteration   2: 7.656 ops/ms
Iteration   3: 7.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.606 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (7.459, 7.606, 7.704), stdev = 0.130
  CI (99.9%): [5.232, 9.981] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ops/ms
# Warmup Iteration   2: 7.515 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.331 ops/ms
Iteration   3: 8.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.439 ±(99.9%) 4.121 ops/ms [Average]
  (min, avg, max) = (8.287, 8.439, 8.699), stdev = 0.226
  CI (99.9%): [4.318, 12.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 7.627 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.999 ops/ms
Iteration   3: 7.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.856 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (7.733, 7.856, 7.999), stdev = 0.134
  CI (99.9%): [5.411, 10.301] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ops/ms
# Warmup Iteration   2: 5.845 ops/ms
# Warmup Iteration   3: 5.765 ops/ms
Iteration   1: 6.228 ops/ms
Iteration   2: 6.378 ops/ms
Iteration   3: 6.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.251 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (6.146, 6.251, 6.378), stdev = 0.118
  CI (99.9%): [4.102, 8.399] (assumes normal distribution)


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
# Warmup Iteration   1: 6.460 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.005 ms/op
Iteration   1: 3.867 ±(99.9%) 0.002 ms/op
Iteration   2: 4.031 ±(99.9%) 0.003 ms/op
Iteration   3: 4.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.997 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (3.867, 3.997, 4.093), stdev = 0.117
  CI (99.9%): [1.865, 6.129] (assumes normal distribution)


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.002 ms/op
Iteration   1: 3.856 ±(99.9%) 0.002 ms/op
Iteration   2: 3.641 ±(99.9%) 0.002 ms/op
Iteration   3: 3.696 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.731 ±(99.9%) 2.037 ms/op [Average]
  (min, avg, max) = (3.641, 3.731, 3.856), stdev = 0.112
  CI (99.9%): [1.694, 5.768] (assumes normal distribution)


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
# Warmup Iteration   1: 5.426 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.005 ms/op
Iteration   1: 3.734 ±(99.9%) 0.002 ms/op
Iteration   2: 3.909 ±(99.9%) 0.002 ms/op
Iteration   3: 3.774 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.805 ±(99.9%) 1.677 ms/op [Average]
  (min, avg, max) = (3.734, 3.805, 3.909), stdev = 0.092
  CI (99.9%): [2.129, 5.482] (assumes normal distribution)


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
# Warmup Iteration   1: 6.991 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.016 ms/op
Iteration   1: 5.078 ±(99.9%) 0.029 ms/op
Iteration   2: 4.896 ±(99.9%) 0.011 ms/op
Iteration   3: 4.994 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.989 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (4.896, 4.989, 5.078), stdev = 0.091
  CI (99.9%): [3.324, 6.654] (assumes normal distribution)


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
# Warmup Iteration   1: 5.012 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.009 ms/op
Iteration   1: 3.680 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  11.556 ms/op
                 createUser·p0.9999: 30.179 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 22.336 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.494 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 22.368 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253369
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4524 
    [ 2.500,  5.000) = 234223 
    [ 5.000,  7.500) = 13408 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     10.988 ms/op
     p(99.9900) =     28.858 ms/op
     p(99.9990) =     30.559 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 5.203 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  11.879 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 3.884 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 17.490 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  10.052 ms/op
                 existUser·p0.9999: 20.105 ms/op
                 existUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244891
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4504 
    [ 2.500,  5.000) = 222336 
    [ 5.000,  7.500) = 16616 
    [ 7.500, 10.000) = 1149 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     10.291 ms/op
     p(99.9900) =     17.810 ms/op
     p(99.9990) =     20.451 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 6.180 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  9.840 ms/op
                 getUser·p0.9999: 19.365 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  11.807 ms/op
                 getUser·p0.9999: 24.434 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  16.382 ms/op
                 getUser·p0.9999: 24.914 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237017
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3483 
    [ 2.500,  5.000) = 211202 
    [ 5.000,  7.500) = 20592 
    [ 7.500, 10.000) = 1297 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.904 ms/op
     p(99.9000) =     12.107 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 7.261 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.655 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.199 ±(99.9%) 0.016 ms/op
Iteration   1: 5.141 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.371 ms/op
                 listUser·p0.999:  15.021 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 5.161 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.285 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 18.199 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 5.095 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  18.373 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186997
  mean =      5.132 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 97394 
    [ 5.000,  7.500) = 82045 
    [ 7.500, 10.000) = 6389 
    [10.000, 12.500) = 635 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     20.870 ms/op
     p(99.9990) =     21.902 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.606 ± 2.374  ops/ms
ClientGrpc.existUser                       thrpt       3   8.439 ± 4.121  ops/ms
ClientGrpc.getUser                         thrpt       3   7.856 ± 2.445  ops/ms
ClientGrpc.listUser                        thrpt       3   6.251 ± 2.149  ops/ms
ClientGrpc.createUser                       avgt       3   3.997 ± 2.132   ms/op
ClientGrpc.existUser                        avgt       3   3.731 ± 2.037   ms/op
ClientGrpc.getUser                          avgt       3   3.805 ± 1.677   ms/op
ClientGrpc.listUser                         avgt       3   4.989 ± 1.665   ms/op
ClientGrpc.createUser                     sample  253369   3.789 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.742           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.079           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.283           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.988           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.858           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.867           ms/op
ClientGrpc.existUser                      sample  244891   3.919 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.611           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.291           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.546           ms/op
ClientGrpc.getUser                        sample  237017   4.049 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.904           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.412           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  186997   5.132 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.826           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.316           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.870           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
