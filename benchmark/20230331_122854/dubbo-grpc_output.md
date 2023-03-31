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
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 5.513 ops/ms
# Warmup Iteration   3: 7.415 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.611 ±(99.9%) 3.892 ops/ms [Average]
  (min, avg, max) = (7.371, 7.611, 7.780), stdev = 0.213
  CI (99.9%): [3.719, 11.502] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.243 ops/ms
Iteration   1: 8.517 ops/ms
Iteration   2: 8.740 ops/ms
Iteration   3: 8.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.657 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (8.517, 8.657, 8.740), stdev = 0.122
  CI (99.9%): [6.424, 10.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.404 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 7.648 ops/ms
Iteration   1: 7.816 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.885 ±(99.9%) 3.893 ops/ms [Average]
  (min, avg, max) = (7.715, 7.885, 8.124), stdev = 0.213
  CI (99.9%): [3.992, 11.778] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ops/ms
# Warmup Iteration   2: 5.553 ops/ms
# Warmup Iteration   3: 5.820 ops/ms
Iteration   1: 6.063 ops/ms
Iteration   2: 5.996 ops/ms
Iteration   3: 6.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.036 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (5.996, 6.036, 6.063), stdev = 0.036
  CI (99.9%): [5.387, 6.686] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.418 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.005 ms/op
Iteration   1: 4.136 ±(99.9%) 0.003 ms/op
Iteration   2: 4.102 ±(99.9%) 0.003 ms/op
Iteration   3: 4.038 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.092 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (4.038, 4.092, 4.136), stdev = 0.050
  CI (99.9%): [3.185, 4.999] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.115 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.004 ms/op
Iteration   1: 3.845 ±(99.9%) 0.005 ms/op
Iteration   2: 3.793 ±(99.9%) 0.007 ms/op
Iteration   3: 3.687 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.775 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (3.687, 3.775, 3.845), stdev = 0.081
  CI (99.9%): [2.305, 5.244] (assumes normal distribution)


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
# Warmup Iteration   1: 6.269 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.006 ms/op
Iteration   1: 4.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.949 ±(99.9%) 0.003 ms/op
Iteration   3: 4.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.043 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (3.949, 4.043, 4.147), stdev = 0.099
  CI (99.9%): [2.237, 5.850] (assumes normal distribution)


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
# Warmup Iteration   1: 7.627 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.788 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.013 ms/op
Iteration   1: 5.188 ±(99.9%) 0.025 ms/op
Iteration   2: 5.156 ±(99.9%) 0.008 ms/op
Iteration   3: 5.261 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.202 ±(99.9%) 0.981 ms/op [Average]
  (min, avg, max) = (5.156, 5.202, 5.261), stdev = 0.054
  CI (99.9%): [4.221, 6.183] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.653 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.014 ms/op
Iteration   1: 4.039 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.807 ms/op
                 createUser·p0.999:  14.670 ms/op
                 createUser·p0.9999: 20.454 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 4.136 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  14.587 ms/op
                 createUser·p0.9999: 21.612 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  14.710 ms/op
                 createUser·p0.9999: 24.500 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233216
  mean =      4.119 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4414 
    [ 2.500,  5.000) = 194301 
    [ 5.000,  7.500) = 31297 
    [ 7.500, 10.000) = 2538 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     22.949 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 6.064 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.013 ms/op
Iteration   1: 3.895 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  13.660 ms/op
                 existUser·p0.9999: 16.797 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 3.828 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  10.264 ms/op
                 existUser·p0.9999: 22.227 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.783 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.447 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250196
  mean =      3.835 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8015 
    [ 2.500,  5.000) = 219910 
    [ 5.000,  7.500) = 19912 
    [ 7.500, 10.000) = 1816 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     12.825 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.528 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.487 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.400 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   7.859 ms/op
                 getUser·p0.999:  12.441 ms/op
                 getUser·p0.9999: 14.731 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 4.012 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   8.280 ms/op
                 getUser·p0.999:  13.582 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 4.055 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  14.369 ms/op
                 getUser·p0.9999: 29.688 ms/op
                 getUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237247
  mean =      4.046 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5764 
    [ 2.500,  5.000) = 202841 
    [ 5.000,  7.500) = 25201 
    [ 7.500, 10.000) = 2536 
    [10.000, 12.500) = 562 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     13.349 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     30.044 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 7.957 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.728 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.244 ±(99.9%) 0.020 ms/op
Iteration   1: 5.240 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  15.053 ms/op
                 listUser·p0.9999: 18.270 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 5.243 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  20.473 ms/op
                 listUser·p0.9999: 57.147 ms/op
                 listUser·p1.00:   60.293 ms/op

Iteration   3: 5.054 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.832 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  21.813 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185497
  mean =      5.177 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 105013 
    [ 5.000, 10.000) = 77765 
    [10.000, 15.000) = 2381 
    [15.000, 20.000) = 188 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     52.232 ms/op
     p(99.9990) =     60.237 ms/op
     p(99.9999) =     60.293 ms/op
    p(100.0000) =     60.293 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.611 ± 3.892  ops/ms
ClientGrpc.existUser                       thrpt       3   8.657 ± 2.234  ops/ms
ClientGrpc.getUser                         thrpt       3   7.885 ± 3.893  ops/ms
ClientGrpc.listUser                        thrpt       3   6.036 ± 0.649  ops/ms
ClientGrpc.createUser                       avgt       3   4.092 ± 0.907   ms/op
ClientGrpc.existUser                        avgt       3   3.775 ± 1.470   ms/op
ClientGrpc.getUser                          avgt       3   4.043 ± 1.806   ms/op
ClientGrpc.listUser                         avgt       3   5.202 ± 0.981   ms/op
ClientGrpc.createUser                     sample  233216   4.119 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.905           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.631           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.949           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  250196   3.835 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.919           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.414           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.825           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  237247   4.046 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.400           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.094           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.349           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.179           ms/op
ClientGrpc.listUser                       sample  185497   5.177 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.440           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.252           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          52.232           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          60.293           ms/op
