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
# Warmup Iteration   1: 2.624 ops/ms
# Warmup Iteration   2: 6.318 ops/ms
# Warmup Iteration   3: 7.415 ops/ms
Iteration   1: 8.087 ops/ms
Iteration   2: 8.018 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.158 ±(99.9%) 3.394 ops/ms [Average]
  (min, avg, max) = (8.018, 8.158, 8.369), stdev = 0.186
  CI (99.9%): [4.764, 11.553] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.669 ops/ms
# Warmup Iteration   2: 8.054 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.860 ops/ms
Iteration   2: 8.462 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.521 ±(99.9%) 5.736 ops/ms [Average]
  (min, avg, max) = (8.239, 8.521, 8.860), stdev = 0.314
  CI (99.9%): [2.785, 14.257] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 7.559 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.219 ops/ms
Iteration   2: 8.135 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.172 ±(99.9%) 0.783 ops/ms [Average]
  (min, avg, max) = (8.135, 8.172, 8.219), stdev = 0.043
  CI (99.9%): [7.389, 8.955] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ops/ms
# Warmup Iteration   2: 5.927 ops/ms
# Warmup Iteration   3: 6.263 ops/ms
Iteration   1: 6.347 ops/ms
Iteration   2: 6.509 ops/ms
Iteration   3: 6.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.485 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (6.347, 6.485, 6.599), stdev = 0.128
  CI (99.9%): [4.156, 8.814] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.005 ms/op
Iteration   1: 3.699 ±(99.9%) 0.004 ms/op
Iteration   2: 3.772 ±(99.9%) 0.002 ms/op
Iteration   3: 3.630 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.700 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.630, 3.700, 3.772), stdev = 0.071
  CI (99.9%): [2.407, 4.994] (assumes normal distribution)


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
# Warmup Iteration   1: 5.170 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.004 ms/op
Iteration   1: 3.478 ±(99.9%) 0.003 ms/op
Iteration   2: 3.582 ±(99.9%) 0.003 ms/op
Iteration   3: 3.533 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.531 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.478, 3.531, 3.582), stdev = 0.052
  CI (99.9%): [2.588, 4.474] (assumes normal distribution)


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.004 ms/op
Iteration   1: 3.838 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.826 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.768, 3.826, 3.872), stdev = 0.053
  CI (99.9%): [2.854, 4.798] (assumes normal distribution)


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
# Warmup Iteration   1: 6.185 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.438 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.035 ±(99.9%) 0.013 ms/op
Iteration   1: 4.940 ±(99.9%) 0.021 ms/op
Iteration   2: 5.029 ±(99.9%) 0.013 ms/op
Iteration   3: 5.204 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.057 ±(99.9%) 2.450 ms/op [Average]
  (min, avg, max) = (4.940, 5.057, 5.204), stdev = 0.134
  CI (99.9%): [2.607, 7.508] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.013 ms/op
Iteration   1: 3.786 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  11.201 ms/op
                 createUser·p0.9999: 19.890 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.882 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  12.954 ms/op
                 createUser·p0.9999: 25.838 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  12.621 ms/op
                 createUser·p0.9999: 33.733 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249530
  mean =      3.844 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7713 
    [ 2.500,  5.000) = 225550 
    [ 5.000,  7.500) = 14143 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     12.345 ms/op
     p(99.9900) =     33.197 ms/op
     p(99.9990) =     34.310 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
Iteration   1: 3.825 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 15.477 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 3.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 20.241 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.465 ms/op
                 existUser·p0.99:   7.633 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 19.883 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248787
  mean =      3.856 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8743 
    [ 2.500,  5.000) = 221368 
    [ 5.000,  7.500) = 16512 
    [ 7.500, 10.000) = 1703 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     11.734 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     20.431 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.631 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  14.133 ms/op
                 getUser·p0.9999: 20.501 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.929 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  12.488 ms/op
                 getUser·p0.9999: 22.835 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 4.050 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  14.076 ms/op
                 getUser·p0.9999: 37.224 ms/op
                 getUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 238825
  mean =      4.018 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7314 
    [ 2.500,  5.000) = 207490 
    [ 5.000,  7.500) = 22017 
    [ 7.500, 10.000) = 1560 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     36.315 ms/op
     p(99.9990) =     38.131 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 6.777 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.549 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.018 ms/op
Iteration   1: 5.041 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.534 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  16.326 ms/op
                 listUser·p0.9999: 18.873 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 5.068 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  17.364 ms/op
                 listUser·p0.9999: 20.603 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 5.041 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.395 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 31.162 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190052
  mean =      5.050 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 359 
    [ 2.500,  5.000) = 117468 
    [ 5.000,  7.500) = 62952 
    [ 7.500, 10.000) = 7738 
    [10.000, 12.500) = 998 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.466 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     18.185 ms/op
     p(99.9900) =     30.834 ms/op
     p(99.9990) =     32.886 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.158 ± 3.394  ops/ms
ClientGrpc.existUser                       thrpt       3   8.521 ± 5.736  ops/ms
ClientGrpc.getUser                         thrpt       3   8.172 ± 0.783  ops/ms
ClientGrpc.listUser                        thrpt       3   6.485 ± 2.329  ops/ms
ClientGrpc.createUser                       avgt       3   3.700 ± 1.294   ms/op
ClientGrpc.existUser                        avgt       3   3.531 ± 0.943   ms/op
ClientGrpc.getUser                          avgt       3   3.826 ± 0.972   ms/op
ClientGrpc.listUser                         avgt       3   5.057 ± 2.450   ms/op
ClientGrpc.createUser                     sample  249530   3.844 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.842           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.345           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.197           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.603           ms/op
ClientGrpc.existUser                      sample  248787   3.856 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.734           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.956           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  238825   4.018 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          36.315           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.339           ms/op
ClientGrpc.listUser                       sample  190052   5.050 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.395           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.466           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.650           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.185           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.834           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.063           ms/op
