# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ops/ms
# Warmup Iteration   2: 6.553 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 8.047 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.107 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (7.944, 8.107, 8.329), stdev = 0.200
  CI (99.9%): [4.466, 11.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.752 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 8.640 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.578 ±(99.9%) 4.483 ops/ms [Average]
  (min, avg, max) = (8.328, 8.578, 8.819), stdev = 0.246
  CI (99.9%): [4.095, 13.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.328 ops/ms
# Warmup Iteration   2: 7.884 ops/ms
# Warmup Iteration   3: 8.229 ops/ms
Iteration   1: 8.547 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.437 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (8.314, 8.437, 8.547), stdev = 0.117
  CI (99.9%): [6.301, 10.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ops/ms
# Warmup Iteration   2: 5.593 ops/ms
# Warmup Iteration   3: 6.231 ops/ms
Iteration   1: 6.136 ops/ms
Iteration   2: 6.443 ops/ms
Iteration   3: 6.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.301 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (6.136, 6.301, 6.443), stdev = 0.155
  CI (99.9%): [3.476, 9.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.331 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.013 ms/op
Iteration   1: 3.755 ±(99.9%) 0.005 ms/op
Iteration   2: 3.868 ±(99.9%) 0.003 ms/op
Iteration   3: 3.674 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.766 ±(99.9%) 1.778 ms/op [Average]
  (min, avg, max) = (3.674, 3.766, 3.868), stdev = 0.097
  CI (99.9%): [1.988, 5.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.219 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.010 ms/op
Iteration   1: 3.554 ±(99.9%) 0.002 ms/op
Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
Iteration   3: 3.640 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.585 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.554, 3.585, 3.640), stdev = 0.048
  CI (99.9%): [2.712, 4.458] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.041 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.004 ms/op
Iteration   1: 3.924 ±(99.9%) 0.006 ms/op
Iteration   2: 3.840 ±(99.9%) 0.003 ms/op
Iteration   3: 3.866 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.877 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (3.840, 3.877, 3.924), stdev = 0.043
  CI (99.9%): [3.094, 4.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.244 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.109 ±(99.9%) 0.018 ms/op
Iteration   1: 5.104 ±(99.9%) 0.021 ms/op
Iteration   2: 4.994 ±(99.9%) 0.013 ms/op
Iteration   3: 4.789 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.962 ±(99.9%) 2.922 ms/op [Average]
  (min, avg, max) = (4.789, 4.962, 5.104), stdev = 0.160
  CI (99.9%): [2.041, 7.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.741 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  14.156 ms/op
                 createUser·p0.9999: 21.052 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.776 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  13.713 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   3: 3.727 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.902 ms/op
                 createUser·p0.999:  13.391 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256026
  mean =      3.752 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9115 
    [ 2.500,  5.000) = 233594 
    [ 5.000,  7.500) = 11426 
    [ 7.500, 10.000) = 1334 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.647 ms/op
     p(99.9900) =     31.700 ms/op
     p(99.9990) =     32.291 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.010 ms/op
Iteration   1: 3.645 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.284 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 15.195 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 3.520 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  9.424 ms/op
                 existUser·p0.9999: 17.231 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 3.709 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  11.300 ms/op
                 existUser·p0.9999: 18.198 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264857
  mean =      3.623 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5924 
    [ 2.500,  5.000) = 248736 
    [ 5.000,  7.500) = 8657 
    [ 7.500, 10.000) = 1219 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.672 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     17.794 ms/op
     p(99.9990) =     19.166 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.083 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.011 ms/op
Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.745 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  10.676 ms/op
                 getUser·p0.9999: 38.273 ms/op
                 getUser·p1.00:   38.732 ms/op

Iteration   3: 3.598 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  8.488 ms/op
                 getUser·p0.9999: 24.612 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259829
  mean =      3.693 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10201 
    [ 2.500,  5.000) = 238757 
    [ 5.000,  7.500) = 9238 
    [ 7.500, 10.000) = 1231 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     11.163 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     38.561 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.077 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.020 ms/op
Iteration   1: 4.852 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.511 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  17.244 ms/op
                 listUser·p0.9999: 19.601 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 5.009 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 21.713 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 4.856 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  19.117 ms/op
                 listUser·p0.9999: 29.243 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195638
  mean =      4.905 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 602 
    [ 2.500,  5.000) = 133526 
    [ 5.000,  7.500) = 53073 
    [ 7.500, 10.000) = 6767 
    [10.000, 12.500) = 1119 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     17.805 ms/op
     p(99.9900) =     28.299 ms/op
     p(99.9990) =     29.656 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.107 ± 3.640  ops/ms
ClientGrpc.existUser                       thrpt       3   8.578 ± 4.483  ops/ms
ClientGrpc.getUser                         thrpt       3   8.437 ± 2.136  ops/ms
ClientGrpc.listUser                        thrpt       3   6.301 ± 2.825  ops/ms
ClientGrpc.createUser                       avgt       3   3.766 ± 1.778   ms/op
ClientGrpc.existUser                        avgt       3   3.585 ± 0.873   ms/op
ClientGrpc.getUser                          avgt       3   3.877 ± 0.783   ms/op
ClientGrpc.listUser                         avgt       3   4.962 ± 2.922   ms/op
ClientGrpc.createUser                     sample  256026   3.752 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.955           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.647           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.700           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.309           ms/op
ClientGrpc.existUser                      sample  264857   3.623 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.284           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.672           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.794           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  259829   3.693 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.627           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.163           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          37.814           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.732           ms/op
ClientGrpc.listUser                       sample  195638   4.905 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.511           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.805           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.299           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
