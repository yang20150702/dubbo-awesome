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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.408 ops/ms
# Warmup Iteration   3: 6.970 ops/ms
Iteration   1: 6.718 ops/ms
Iteration   2: 7.047 ops/ms
Iteration   3: 7.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.974 ±(99.9%) 4.173 ops/ms [Average]
  (min, avg, max) = (6.718, 6.974, 7.158), stdev = 0.229
  CI (99.9%): [2.802, 11.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.583 ops/ms
# Warmup Iteration   2: 6.579 ops/ms
# Warmup Iteration   3: 7.027 ops/ms
Iteration   1: 7.079 ops/ms
Iteration   2: 7.847 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.539 ±(99.9%) 7.399 ops/ms [Average]
  (min, avg, max) = (7.079, 7.539, 7.847), stdev = 0.406
  CI (99.9%): [0.140, 14.938] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ops/ms
# Warmup Iteration   2: 6.381 ops/ms
# Warmup Iteration   3: 6.633 ops/ms
Iteration   1: 6.986 ops/ms
Iteration   2: 6.826 ops/ms
Iteration   3: 6.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.900 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (6.826, 6.900, 6.986), stdev = 0.081
  CI (99.9%): [5.423, 8.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 4.589 ops/ms
# Warmup Iteration   3: 5.240 ops/ms
Iteration   1: 4.993 ops/ms
Iteration   2: 5.400 ops/ms
Iteration   3: 5.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.249 ±(99.9%) 4.066 ops/ms [Average]
  (min, avg, max) = (4.993, 5.249, 5.400), stdev = 0.223
  CI (99.9%): [1.183, 9.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.884 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.006 ms/op
Iteration   1: 4.741 ±(99.9%) 0.004 ms/op
Iteration   2: 4.687 ±(99.9%) 0.003 ms/op
Iteration   3: 4.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.642 ±(99.9%) 2.339 ms/op [Average]
  (min, avg, max) = (4.497, 4.642, 4.741), stdev = 0.128
  CI (99.9%): [2.303, 6.981] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.235 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.004 ms/op
Iteration   1: 4.292 ±(99.9%) 0.004 ms/op
Iteration   2: 4.299 ±(99.9%) 0.002 ms/op
Iteration   3: 4.431 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.341 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (4.292, 4.341, 4.431), stdev = 0.079
  CI (99.9%): [2.905, 5.776] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.082 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.002 ms/op
Iteration   1: 4.753 ±(99.9%) 0.006 ms/op
Iteration   2: 4.696 ±(99.9%) 0.004 ms/op
Iteration   3: 4.663 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.704 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (4.663, 4.704, 4.753), stdev = 0.045
  CI (99.9%): [3.879, 5.529] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.787 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 6.202 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.798 ±(99.9%) 0.012 ms/op
Iteration   1: 5.797 ±(99.9%) 0.017 ms/op
Iteration   2: 5.820 ±(99.9%) 0.021 ms/op
Iteration   3: 5.934 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.850 ±(99.9%) 1.332 ms/op [Average]
  (min, avg, max) = (5.797, 5.850, 5.934), stdev = 0.073
  CI (99.9%): [4.519, 7.182] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.159 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.800 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.630 ±(99.9%) 0.015 ms/op
Iteration   1: 4.387 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   8.208 ms/op
                 createUser·p0.999:  15.484 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 4.652 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  19.738 ms/op
                 createUser·p0.9999: 26.615 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 4.571 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  16.677 ms/op
                 createUser·p0.9999: 28.770 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211816
  mean =      4.534 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3144 
    [ 2.500,  5.000) = 158861 
    [ 5.000,  7.500) = 46119 
    [ 7.500, 10.000) = 2711 
    [10.000, 12.500) = 618 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     26.596 ms/op
     p(99.9990) =     29.115 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.451 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.012 ms/op
Iteration   1: 4.393 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   6.013 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  16.341 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 4.428 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.480 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  15.128 ms/op
                 existUser·p0.9999: 21.048 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 4.269 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  12.798 ms/op
                 existUser·p0.9999: 21.547 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219998
  mean =      4.362 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4284 
    [ 2.500,  5.000) = 175588 
    [ 5.000,  7.500) = 37138 
    [ 7.500, 10.000) = 1987 
    [10.000, 12.500) = 635 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     22.276 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.889 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.983 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.679 ±(99.9%) 0.015 ms/op
Iteration   1: 4.718 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  13.176 ms/op
                 getUser·p0.9999: 16.251 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 4.698 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  13.648 ms/op
                 getUser·p0.9999: 19.810 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 4.611 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   7.909 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 19.728 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 205274
  mean =      4.675 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2682 
    [ 2.500,  5.000) = 140894 
    [ 5.000,  7.500) = 57838 
    [ 7.500, 10.000) = 2994 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     19.331 ms/op
     p(99.9990) =     20.052 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.645 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 6.341 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.881 ±(99.9%) 0.022 ms/op
Iteration   1: 5.682 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.760 ms/op
                 listUser·p0.999:  18.001 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 5.746 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.607 ms/op
                 listUser·p0.999:  16.723 ms/op
                 listUser·p0.9999: 19.912 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 5.708 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.952 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 24.215 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167989
  mean =      5.712 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 42053 
    [ 5.000,  7.500) = 114188 
    [ 7.500, 10.000) = 9346 
    [10.000, 12.500) = 1693 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     26.300 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.974 ± 4.173  ops/ms
ClientGrpc.existUser                       thrpt       3   7.539 ± 7.399  ops/ms
ClientGrpc.getUser                         thrpt       3   6.900 ± 1.477  ops/ms
ClientGrpc.listUser                        thrpt       3   5.249 ± 4.066  ops/ms
ClientGrpc.createUser                       avgt       3   4.642 ± 2.339   ms/op
ClientGrpc.existUser                        avgt       3   4.341 ± 1.435   ms/op
ClientGrpc.getUser                          avgt       3   4.704 ± 0.825   ms/op
ClientGrpc.listUser                         avgt       3   5.850 ± 1.332   ms/op
ClientGrpc.createUser                     sample  211816   4.534 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.934           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.160           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.384           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.596           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  219998   4.362 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.055           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.184           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.090           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.906           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.200           ms/op
ClientGrpc.getUser                        sample  205274   4.675 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.929           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.775           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.291           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.700           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.331           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  167989   5.712 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.958           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.568           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.826           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
