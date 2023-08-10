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
# Warmup Iteration   1: 3.438 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 9.741 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.210 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (10.053, 10.210, 10.303), stdev = 0.137
  CI (99.9%): [7.712, 12.708] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.252 ops/ms
# Warmup Iteration   2: 10.461 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 10.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.786 ±(99.9%) 3.998 ops/ms [Average]
  (min, avg, max) = (10.543, 10.786, 10.970), stdev = 0.219
  CI (99.9%): [6.788, 14.784] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.687 ops/ms
# Warmup Iteration   2: 9.839 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.305 ±(99.9%) 4.340 ops/ms [Average]
  (min, avg, max) = (10.159, 10.305, 10.580), stdev = 0.238
  CI (99.9%): [5.966, 14.645] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.192 ops/ms
# Warmup Iteration   2: 7.292 ops/ms
# Warmup Iteration   3: 7.594 ops/ms
Iteration   1: 7.609 ops/ms
Iteration   2: 7.618 ops/ms
Iteration   3: 7.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.616 ±(99.9%) 0.123 ops/ms [Average]
  (min, avg, max) = (7.609, 7.616, 7.622), stdev = 0.007
  CI (99.9%): [7.493, 7.739] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.721 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.003 ms/op
Iteration   1: 3.184 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.114 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.142 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.114, 3.142, 3.184), stdev = 0.037
  CI (99.9%): [2.464, 3.820] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.292 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (2.963, 2.984, 3.011), stdev = 0.025
  CI (99.9%): [2.533, 3.435] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.215 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.083 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.050, 3.083, 3.123), stdev = 0.037
  CI (99.9%): [2.408, 3.758] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.008 ms/op
Iteration   1: 4.139 ±(99.9%) 0.015 ms/op
Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
Iteration   3: 4.090 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.117 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (4.090, 4.117, 4.139), stdev = 0.025
  CI (99.9%): [3.661, 4.572] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
Iteration   1: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 19.713 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.614 ms/op
                 createUser·p0.999:  7.725 ms/op
                 createUser·p0.9999: 19.489 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 3.135 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 36.438 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306683
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15209 
    [ 2.500,  5.000) = 289433 
    [ 5.000,  7.500) = 1485 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     35.935 ms/op
     p(99.9990) =     36.696 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.261 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.442 ms/op
                 existUser·p0.999:  7.820 ms/op
                 existUser·p0.9999: 17.645 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322696
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27850 
    [ 2.500,  5.000) = 293048 
    [ 5.000,  7.500) = 1239 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     19.217 ms/op
     p(99.9990) =     20.105 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.921 ms/op
                 getUser·p0.9999: 16.492 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.720 ms/op
                 getUser·p0.9999: 33.018 ms/op
                 getUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310488
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20380 
    [ 2.500,  5.000) = 287420 
    [ 5.000,  7.500) = 2068 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      8.872 ms/op
     p(99.9900) =     31.546 ms/op
     p(99.9990) =     33.223 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 5.840 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.012 ms/op
Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.688 ms/op
                 listUser·p0.9999: 14.699 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 23.210 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.399 ms/op
                 listUser·p0.9999: 28.808 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236213
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1419 
    [ 2.500,  5.000) = 209321 
    [ 5.000,  7.500) = 23260 
    [ 7.500, 10.000) = 1541 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     27.665 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.210 ± 2.498  ops/ms
ClientGrpc.existUser                       thrpt       3  10.786 ± 3.998  ops/ms
ClientGrpc.getUser                         thrpt       3  10.305 ± 4.340  ops/ms
ClientGrpc.listUser                        thrpt       3   7.616 ± 0.123  ops/ms
ClientGrpc.createUser                       avgt       3   3.142 ± 0.678   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 0.451   ms/op
ClientGrpc.getUser                          avgt       3   3.083 ± 0.675   ms/op
ClientGrpc.listUser                         avgt       3   4.117 ± 0.455   ms/op
ClientGrpc.createUser                     sample  306683   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.727           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.935           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.766           ms/op
ClientGrpc.existUser                      sample  322696   2.973 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  310488   3.090 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.872           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.546           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817           ms/op
ClientGrpc.listUser                       sample  236213   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.665           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
