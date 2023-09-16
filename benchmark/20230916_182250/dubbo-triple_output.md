# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.664 ops/ms
# Warmup Iteration   3: 8.384 ops/ms
Iteration   1: 9.155 ops/ms
Iteration   2: 9.254 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.260 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (9.155, 9.260, 9.370), stdev = 0.108
  CI (99.9%): [7.295, 11.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.839 ops/ms
# Warmup Iteration   2: 8.750 ops/ms
# Warmup Iteration   3: 9.509 ops/ms
Iteration   1: 9.795 ops/ms
Iteration   2: 9.989 ops/ms
Iteration   3: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.764 ±(99.9%) 4.417 ops/ms [Average]
  (min, avg, max) = (9.508, 9.764, 9.989), stdev = 0.242
  CI (99.9%): [5.348, 14.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.536 ops/ms
# Warmup Iteration   3: 9.050 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.451 ops/ms
Iteration   3: 9.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.393 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (9.339, 9.393, 9.451), stdev = 0.056
  CI (99.9%): [8.373, 10.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.984 ops/ms
# Warmup Iteration   2: 7.055 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.888 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (7.825, 7.888, 7.955), stdev = 0.065
  CI (99.9%): [6.705, 9.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.150 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.004 ms/op
Iteration   1: 3.454 ±(99.9%) 0.007 ms/op
Iteration   2: 3.345 ±(99.9%) 0.005 ms/op
Iteration   3: 3.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.408 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.345, 3.408, 3.454), stdev = 0.057
  CI (99.9%): [2.377, 4.439] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.083 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.004 ms/op
Iteration   1: 3.302 ±(99.9%) 0.005 ms/op
Iteration   2: 3.381 ±(99.9%) 0.004 ms/op
Iteration   3: 3.244 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.309 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (3.244, 3.309, 3.381), stdev = 0.069
  CI (99.9%): [2.054, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.805 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.003 ms/op
Iteration   1: 3.477 ±(99.9%) 0.005 ms/op
Iteration   2: 3.461 ±(99.9%) 0.003 ms/op
Iteration   3: 3.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.488 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.461, 3.488, 3.527), stdev = 0.034
  CI (99.9%): [2.866, 4.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.720 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.004 ms/op
Iteration   1: 4.058 ±(99.9%) 0.004 ms/op
Iteration   2: 4.082 ±(99.9%) 0.002 ms/op
Iteration   3: 4.037 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.059 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (4.037, 4.059, 4.082), stdev = 0.023
  CI (99.9%): [3.643, 4.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.264 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  20.652 ms/op
                 createUser·p0.9999: 23.158 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  22.046 ms/op
                 createUser·p0.9999: 25.770 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.518 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.985 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 24.966 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276797
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7993 
    [ 2.500,  5.000) = 263331 
    [ 5.000,  7.500) = 4193 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     18.455 ms/op
     p(99.9900) =     24.718 ms/op
     p(99.9990) =     26.172 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.177 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
Iteration   1: 3.339 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  19.273 ms/op
                 existUser·p0.9999: 21.444 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.379 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.174 ms/op
                 existUser·p0.999:  20.602 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 24.432 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285156
  mean =      3.365 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6816 
    [ 2.500,  5.000) = 273902 
    [ 5.000,  7.500) = 3574 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     14.080 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.811 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.011 ms/op
Iteration   1: 3.620 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  19.481 ms/op
                 getUser·p0.9999: 22.582 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.470 ms/op
                 getUser·p0.999:  21.244 ms/op
                 getUser·p0.9999: 25.056 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  18.110 ms/op
                 getUser·p0.9999: 25.852 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273489
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2994 
    [ 2.500,  5.000) = 262475 
    [ 5.000,  7.500) = 6830 
    [ 7.500, 10.000) = 676 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     18.367 ms/op
     p(99.9900) =     25.122 ms/op
     p(99.9990) =     26.646 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.354 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.012 ms/op
Iteration   1: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 21.798 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 4.047 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 18.222 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.187 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.756 ms/op
                 listUser·p0.9999: 14.982 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234853
  mean =      4.087 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 225933 
    [ 5.000,  7.500) = 7089 
    [ 7.500, 10.000) = 1112 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.795 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     21.021 ms/op
     p(99.9990) =     23.723 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.260 ± 1.965  ops/ms
ClientPb.existUser                       thrpt       3   9.764 ± 4.417  ops/ms
ClientPb.getUser                         thrpt       3   9.393 ± 1.020  ops/ms
ClientPb.listUser                        thrpt       3   7.888 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   3.408 ± 1.031   ms/op
ClientPb.existUser                        avgt       3   3.309 ± 1.255   ms/op
ClientPb.getUser                          avgt       3   3.488 ± 0.623   ms/op
ClientPb.listUser                         avgt       3   4.059 ± 0.416   ms/op
ClientPb.createUser                     sample  276797   3.466 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.368           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.455           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.718           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.477           ms/op
ClientPb.existUser                      sample  285156   3.365 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.013           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.080           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  273489   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.122           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.918           ms/op
ClientPb.listUser                       sample  234853   4.087 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.795           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.021           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
