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
# Warmup Iteration   1: 1.233 ops/ms
# Warmup Iteration   2: 3.195 ops/ms
# Warmup Iteration   3: 5.921 ops/ms
Iteration   1: 6.066 ops/ms
Iteration   2: 6.266 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.210 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (6.066, 6.210, 6.298), stdev = 0.125
  CI (99.9%): [3.920, 8.499] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.551 ops/ms
# Warmup Iteration   2: 5.350 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 6.918 ops/ms
Iteration   2: 6.989 ops/ms
Iteration   3: 6.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.940 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (6.911, 6.940, 6.989), stdev = 0.043
  CI (99.9%): [6.150, 7.729] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.886 ops/ms
# Warmup Iteration   2: 5.254 ops/ms
# Warmup Iteration   3: 6.033 ops/ms
Iteration   1: 6.028 ops/ms
Iteration   2: 6.344 ops/ms
Iteration   3: 6.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.130 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (6.018, 6.130, 6.344), stdev = 0.185
  CI (99.9%): [2.752, 9.507] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.461 ops/ms
# Warmup Iteration   2: 4.157 ops/ms
# Warmup Iteration   3: 4.983 ops/ms
Iteration   1: 5.343 ops/ms
Iteration   2: 5.253 ops/ms
Iteration   3: 5.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.314 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (5.253, 5.314, 5.345), stdev = 0.053
  CI (99.9%): [4.349, 6.278] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.956 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.365 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.643 ±(99.9%) 0.009 ms/op
Iteration   1: 5.108 ±(99.9%) 0.009 ms/op
Iteration   2: 5.116 ±(99.9%) 0.009 ms/op
Iteration   3: 5.250 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.158 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (5.108, 5.158, 5.250), stdev = 0.080
  CI (99.9%): [3.699, 6.617] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.960 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.735 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.013 ms/op
Iteration   1: 5.049 ±(99.9%) 0.008 ms/op
Iteration   2: 4.875 ±(99.9%) 0.011 ms/op
Iteration   3: 4.930 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.951 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (4.875, 4.951, 5.049), stdev = 0.089
  CI (99.9%): [3.333, 6.569] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.469 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.831 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.010 ms/op
Iteration   1: 5.176 ±(99.9%) 0.010 ms/op
Iteration   2: 5.136 ±(99.9%) 0.008 ms/op
Iteration   3: 5.118 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.143 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (5.118, 5.143, 5.176), stdev = 0.030
  CI (99.9%): [4.596, 5.690] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.232 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 7.251 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.083 ±(99.9%) 0.012 ms/op
Iteration   1: 5.744 ±(99.9%) 0.016 ms/op
Iteration   2: 5.867 ±(99.9%) 0.017 ms/op
Iteration   3: 5.588 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.733 ±(99.9%) 2.546 ms/op [Average]
  (min, avg, max) = (5.588, 5.733, 5.867), stdev = 0.140
  CI (99.9%): [3.187, 8.279] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.134 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 6.493 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.428 ±(99.9%) 0.023 ms/op
Iteration   1: 5.162 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  22.676 ms/op
                 createUser·p0.9999: 26.962 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 5.178 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.815 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  24.369 ms/op
                 createUser·p0.9999: 30.435 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 5.332 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.701 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  28.048 ms/op
                 createUser·p0.9999: 52.428 ms/op
                 createUser·p1.00:   55.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 183853
  mean =      5.223 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 100414 
    [ 5.000, 10.000) = 81543 
    [10.000, 15.000) = 1609 
    [15.000, 20.000) = 88 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     48.803 ms/op
     p(99.9990) =     53.750 ms/op
     p(99.9999) =     55.509 ms/op
    p(100.0000) =     55.509 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.295 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.011 ±(99.9%) 0.018 ms/op
Iteration   1: 5.026 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.382 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  21.466 ms/op
                 existUser·p0.9999: 29.983 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   2: 4.950 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  18.407 ms/op
                 existUser·p0.9999: 26.211 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   3: 4.857 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   10.078 ms/op
                 existUser·p0.999:  16.386 ms/op
                 existUser·p0.9999: 31.176 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194157
  mean =      4.943 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 138016 
    [ 5.000,  7.500) = 47995 
    [ 7.500, 10.000) = 6038 
    [10.000, 12.500) = 1475 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     17.314 ms/op
     p(99.9900) =     30.709 ms/op
     p(99.9990) =     31.436 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.970 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.548 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.214 ±(99.9%) 0.019 ms/op
Iteration   1: 5.265 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   8.326 ms/op
                 getUser·p0.99:   12.354 ms/op
                 getUser·p0.999:  21.542 ms/op
                 getUser·p0.9999: 26.722 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 5.298 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.848 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  23.614 ms/op
                 getUser·p0.9999: 27.095 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 4.965 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  21.801 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185442
  mean =      5.172 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 111186 
    [ 5.000,  7.500) = 64227 
    [ 7.500, 10.000) = 7152 
    [10.000, 12.500) = 1824 
    [12.500, 15.000) = 592 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     27.245 ms/op
     p(99.9990) =     28.299 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.303 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.417 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.782 ±(99.9%) 0.022 ms/op
Iteration   1: 6.022 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  25.817 ms/op
                 listUser·p0.9999: 31.404 ms/op
                 listUser·p1.00:   32.276 ms/op

Iteration   2: 5.714 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   6.889 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  25.788 ms/op
                 listUser·p0.9999: 29.139 ms/op
                 listUser·p1.00:   30.343 ms/op

Iteration   3: 5.890 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  22.262 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163395
  mean =      5.873 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 24634 
    [ 5.000,  7.500) = 127045 
    [ 7.500, 10.000) = 8710 
    [10.000, 12.500) = 1896 
    [12.500, 15.000) = 606 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     11.388 ms/op
     p(99.9000) =     24.497 ms/op
     p(99.9900) =     28.956 ms/op
     p(99.9990) =     32.027 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.210 ± 2.289  ops/ms
ClientPb.existUser                       thrpt       3   6.940 ± 0.790  ops/ms
ClientPb.getUser                         thrpt       3   6.130 ± 3.378  ops/ms
ClientPb.listUser                        thrpt       3   5.314 ± 0.964  ops/ms
ClientPb.createUser                       avgt       3   5.158 ± 1.459   ms/op
ClientPb.existUser                        avgt       3   4.951 ± 1.618   ms/op
ClientPb.getUser                          avgt       3   5.143 ± 0.547   ms/op
ClientPb.listUser                         avgt       3   5.733 ± 2.546   ms/op
ClientPb.createUser                     sample  183853   5.223 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.815           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.423           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.060           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.872           ms/op
ClientPb.createUser:createUser·p0.9999  sample          48.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          55.509           ms/op
ClientPb.existUser                      sample  194157   4.943 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.728           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.225           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.060           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.314           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.709           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.145           ms/op
ClientPb.getUser                        sample  185442   5.172 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.561           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.889           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  163395   5.873 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.388           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.497           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.956           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.276           ms/op
