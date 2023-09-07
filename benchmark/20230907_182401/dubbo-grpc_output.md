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
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 5.121 ops/ms
# Warmup Iteration   3: 6.641 ops/ms
Iteration   1: 6.841 ops/ms
Iteration   2: 6.874 ops/ms
Iteration   3: 6.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.900 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (6.841, 6.900, 6.985), stdev = 0.075
  CI (99.9%): [5.529, 8.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ops/ms
# Warmup Iteration   2: 6.556 ops/ms
# Warmup Iteration   3: 7.144 ops/ms
Iteration   1: 7.363 ops/ms
Iteration   2: 7.552 ops/ms
Iteration   3: 7.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.445 ±(99.9%) 1.769 ops/ms [Average]
  (min, avg, max) = (7.363, 7.445, 7.552), stdev = 0.097
  CI (99.9%): [5.677, 9.214] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ops/ms
# Warmup Iteration   2: 6.418 ops/ms
# Warmup Iteration   3: 7.002 ops/ms
Iteration   1: 7.157 ops/ms
Iteration   2: 7.422 ops/ms
Iteration   3: 7.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.207 ±(99.9%) 3.557 ops/ms [Average]
  (min, avg, max) = (7.041, 7.207, 7.422), stdev = 0.195
  CI (99.9%): [3.650, 10.764] (assumes normal distribution)


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
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 5.058 ops/ms
# Warmup Iteration   3: 5.453 ops/ms
Iteration   1: 5.179 ops/ms
Iteration   2: 5.488 ops/ms
Iteration   3: 5.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.441 ±(99.9%) 4.429 ops/ms [Average]
  (min, avg, max) = (5.179, 5.441, 5.657), stdev = 0.243
  CI (99.9%): [1.012, 9.870] (assumes normal distribution)


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
# Warmup Iteration   1: 7.466 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.649 ±(99.9%) 0.020 ms/op
Iteration   1: 4.293 ±(99.9%) 0.003 ms/op
Iteration   2: 4.357 ±(99.9%) 0.005 ms/op
Iteration   3: 4.371 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.340 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (4.293, 4.340, 4.371), stdev = 0.041
  CI (99.9%): [3.584, 5.096] (assumes normal distribution)


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
# Warmup Iteration   1: 7.355 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.974 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.031 ms/op
Iteration   1: 4.213 ±(99.9%) 0.004 ms/op
Iteration   2: 4.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.956 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.061 ±(99.9%) 2.459 ms/op [Average]
  (min, avg, max) = (3.956, 4.061, 4.213), stdev = 0.135
  CI (99.9%): [1.602, 6.521] (assumes normal distribution)


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
# Warmup Iteration   1: 6.694 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.488 ±(99.9%) 0.006 ms/op
Iteration   1: 4.337 ±(99.9%) 0.004 ms/op
Iteration   2: 4.499 ±(99.9%) 0.005 ms/op
Iteration   3: 4.723 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.520 ±(99.9%) 3.537 ms/op [Average]
  (min, avg, max) = (4.337, 4.520, 4.723), stdev = 0.194
  CI (99.9%): [0.983, 8.057] (assumes normal distribution)


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
# Warmup Iteration   1: 9.280 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.295 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.971 ±(99.9%) 0.017 ms/op
Iteration   1: 6.089 ±(99.9%) 0.031 ms/op
Iteration   2: 5.898 ±(99.9%) 0.025 ms/op
Iteration   3: 5.967 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.985 ±(99.9%) 1.759 ms/op [Average]
  (min, avg, max) = (5.898, 5.985, 6.089), stdev = 0.096
  CI (99.9%): [4.226, 7.743] (assumes normal distribution)


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
# Warmup Iteration   1: 7.064 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.015 ms/op
Iteration   1: 4.432 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   8.208 ms/op
                 createUser·p0.999:  13.378 ms/op
                 createUser·p0.9999: 20.549 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 4.634 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  14.155 ms/op
                 createUser·p0.9999: 19.179 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 4.650 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.928 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  15.606 ms/op
                 createUser·p0.9999: 43.713 ms/op
                 createUser·p1.00:   50.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210027
  mean =      4.570 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 156109 
    [ 5.000, 10.000) = 52901 
    [10.000, 15.000) = 864 
    [15.000, 20.000) = 79 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 13 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     49.498 ms/op
     p(99.9999) =     50.070 ms/op
    p(100.0000) =     50.070 ms/op


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
# Warmup Iteration   1: 7.472 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.013 ms/op
Iteration   1: 4.209 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.882 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  11.371 ms/op
                 existUser·p0.9999: 15.971 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   2: 4.180 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   8.241 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 29.601 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 4.252 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  18.537 ms/op
                 existUser·p0.9999: 22.477 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227780
  mean =      4.213 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9161 
    [ 2.500,  5.000) = 187829 
    [ 5.000,  7.500) = 27028 
    [ 7.500, 10.000) = 2821 
    [10.000, 12.500) = 590 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     29.047 ms/op
     p(99.9990) =     29.810 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 7.284 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.015 ms/op
Iteration   1: 4.518 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  15.407 ms/op
                 getUser·p0.9999: 16.566 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 4.505 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.152 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  13.697 ms/op
                 getUser·p0.9999: 19.788 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 4.451 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  13.773 ms/op
                 getUser·p0.9999: 21.379 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213828
  mean =      4.491 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4933 
    [ 2.500,  5.000) = 161377 
    [ 5.000,  7.500) = 43562 
    [ 7.500, 10.000) = 2743 
    [10.000, 12.500) = 765 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     15.046 ms/op
     p(99.9900) =     20.455 ms/op
     p(99.9990) =     24.603 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 9.249 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.189 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.767 ±(99.9%) 0.021 ms/op
Iteration   1: 5.840 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 5.677 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  19.880 ms/op
                 listUser·p0.9999: 23.183 ms/op
                 listUser·p1.00:   29.950 ms/op

Iteration   3: 5.659 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.162 ms/op
                 listUser·p0.999:  21.753 ms/op
                 listUser·p0.9999: 31.852 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167645
  mean =      5.724 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 54838 
    [ 5.000,  7.500) = 95679 
    [ 7.500, 10.000) = 13802 
    [10.000, 12.500) = 2261 
    [12.500, 15.000) = 551 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     19.181 ms/op
     p(99.9900) =     27.992 ms/op
     p(99.9990) =     32.766 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.900 ± 1.371  ops/ms
ClientGrpc.existUser                       thrpt       3   7.445 ± 1.769  ops/ms
ClientGrpc.getUser                         thrpt       3   7.207 ± 3.557  ops/ms
ClientGrpc.listUser                        thrpt       3   5.441 ± 4.429  ops/ms
ClientGrpc.createUser                       avgt       3   4.340 ± 0.756   ms/op
ClientGrpc.existUser                        avgt       3   4.061 ± 2.459   ms/op
ClientGrpc.getUser                          avgt       3   4.520 ± 3.537   ms/op
ClientGrpc.listUser                         avgt       3   5.985 ± 1.759   ms/op
ClientGrpc.createUser                     sample  210027   4.570 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.431           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.798           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.156           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.683           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          50.070           ms/op
ClientGrpc.existUser                      sample  227780   4.213 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.821           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.090           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.047           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.917           ms/op
ClientGrpc.getUser                        sample  213828   4.491 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.831           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.046           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.455           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.805           ms/op
ClientGrpc.listUser                       sample  167645   5.724 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.210           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.520           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.239           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.181           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.992           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.899           ms/op
