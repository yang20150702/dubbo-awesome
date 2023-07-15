# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.203 ops/ms
# Warmup Iteration   2: 2.800 ops/ms
# Warmup Iteration   3: 6.030 ops/ms
Iteration   1: 6.155 ops/ms
Iteration   2: 6.103 ops/ms
Iteration   3: 6.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.128 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (6.103, 6.128, 6.155), stdev = 0.026
  CI (99.9%): [5.656, 6.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.951 ops/ms
# Warmup Iteration   2: 5.081 ops/ms
# Warmup Iteration   3: 6.462 ops/ms
Iteration   1: 6.726 ops/ms
Iteration   2: 6.224 ops/ms
Iteration   3: 6.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.501 ±(99.9%) 4.652 ops/ms [Average]
  (min, avg, max) = (6.224, 6.501, 6.726), stdev = 0.255
  CI (99.9%): [1.849, 11.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.780 ops/ms
# Warmup Iteration   2: 5.081 ops/ms
# Warmup Iteration   3: 6.195 ops/ms
Iteration   1: 6.210 ops/ms
Iteration   2: 6.416 ops/ms
Iteration   3: 6.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.328 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (6.210, 6.328, 6.416), stdev = 0.107
  CI (99.9%): [4.383, 8.272] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.719 ops/ms
# Warmup Iteration   2: 4.552 ops/ms
# Warmup Iteration   3: 5.537 ops/ms
Iteration   1: 5.142 ops/ms
Iteration   2: 5.303 ops/ms
Iteration   3: 5.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.231 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (5.142, 5.231, 5.303), stdev = 0.082
  CI (99.9%): [3.735, 6.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.218 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.234 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.492 ±(99.9%) 0.013 ms/op
Iteration   1: 5.071 ±(99.9%) 0.016 ms/op
Iteration   2: 5.044 ±(99.9%) 0.015 ms/op
Iteration   3: 4.796 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.970 ±(99.9%) 2.762 ms/op [Average]
  (min, avg, max) = (4.796, 4.970, 5.071), stdev = 0.151
  CI (99.9%): [2.208, 7.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.940 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.343 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.883 ±(99.9%) 0.012 ms/op
Iteration   1: 4.883 ±(99.9%) 0.009 ms/op
Iteration   2: 4.924 ±(99.9%) 0.009 ms/op
Iteration   3: 4.804 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.871 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (4.804, 4.871, 4.924), stdev = 0.061
  CI (99.9%): [3.756, 5.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.055 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.983 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.011 ms/op
Iteration   1: 5.372 ±(99.9%) 0.011 ms/op
Iteration   2: 5.038 ±(99.9%) 0.014 ms/op
Iteration   3: 5.123 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.178 ±(99.9%) 3.172 ms/op [Average]
  (min, avg, max) = (5.038, 5.178, 5.372), stdev = 0.174
  CI (99.9%): [2.006, 8.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.487 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.274 ±(99.9%) 0.015 ms/op
Iteration   1: 6.064 ±(99.9%) 0.017 ms/op
Iteration   2: 6.092 ±(99.9%) 0.019 ms/op
Iteration   3: 5.764 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.973 ±(99.9%) 3.313 ms/op [Average]
  (min, avg, max) = (5.764, 5.973, 6.092), stdev = 0.182
  CI (99.9%): [2.661, 9.286] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.754 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.335 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.667 ±(99.9%) 0.025 ms/op
Iteration   1: 4.976 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.889 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  19.342 ms/op
                 createUser·p0.9999: 26.331 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 5.012 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.054 ms/op
                 createUser·p0.95:   6.660 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  18.265 ms/op
                 createUser·p0.9999: 26.661 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 5.280 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.073 ms/op
                 createUser·p0.999:  26.378 ms/op
                 createUser·p0.9999: 28.148 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188624
  mean =      5.086 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 110858 
    [ 5.000,  7.500) = 71119 
    [ 7.500, 10.000) = 5387 
    [10.000, 12.500) = 680 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.259 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     21.479 ms/op
     p(99.9900) =     27.530 ms/op
     p(99.9990) =     29.462 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.754 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.409 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.016 ms/op
Iteration   1: 5.057 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.046 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  18.724 ms/op
                 existUser·p0.9999: 22.710 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 5.018 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  21.641 ms/op
                 existUser·p0.9999: 26.560 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 5.203 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.201 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  24.268 ms/op
                 existUser·p0.9999: 26.697 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188194
  mean =      5.091 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 108600 
    [ 5.000,  7.500) = 73344 
    [ 7.500, 10.000) = 4489 
    [10.000, 12.500) = 1042 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.993 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     26.482 ms/op
     p(99.9990) =     27.284 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.047 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.312 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.176 ±(99.9%) 0.018 ms/op
Iteration   1: 5.025 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.560 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  26.004 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   32.997 ms/op

Iteration   2: 5.205 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.114 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  24.439 ms/op
                 getUser·p0.9999: 28.641 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 5.267 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.023 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   6.996 ms/op
                 getUser·p0.99:   9.781 ms/op
                 getUser·p0.999:  26.640 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186119
  mean =      5.164 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 109550 
    [ 5.000,  7.500) = 66878 
    [ 7.500, 10.000) = 7616 
    [10.000, 12.500) = 1174 
    [12.500, 15.000) = 516 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     25.041 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.116 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.567 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.123 ±(99.9%) 0.024 ms/op
Iteration   1: 6.260 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  27.197 ms/op
                 listUser·p0.9999: 31.195 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 5.938 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.148 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  26.872 ms/op
                 listUser·p0.9999: 29.478 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   3: 5.926 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  22.677 ms/op
                 listUser·p0.9999: 25.284 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159033
  mean =      6.037 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 16455 
    [ 5.000,  7.500) = 130422 
    [ 7.500, 10.000) = 9394 
    [10.000, 12.500) = 1671 
    [12.500, 15.000) = 570 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 129 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     29.891 ms/op
     p(99.9990) =     32.521 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.128 ± 0.472  ops/ms
ClientPb.existUser                       thrpt       3   6.501 ± 4.652  ops/ms
ClientPb.getUser                         thrpt       3   6.328 ± 1.944  ops/ms
ClientPb.listUser                        thrpt       3   5.231 ± 1.497  ops/ms
ClientPb.createUser                       avgt       3   4.970 ± 2.762   ms/op
ClientPb.existUser                        avgt       3   4.871 ± 1.114   ms/op
ClientPb.getUser                          avgt       3   5.178 ± 3.172   ms/op
ClientPb.listUser                         avgt       3   5.973 ± 3.313   ms/op
ClientPb.createUser                     sample  188624   5.086 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.530           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  188194   5.091 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.993           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.414           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.482           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  186119   5.164 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.023           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.240           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.524           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  159033   6.037 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.493           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.690           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.891           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.063           ms/op
