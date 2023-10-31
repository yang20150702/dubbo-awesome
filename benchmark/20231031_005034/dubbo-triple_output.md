# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.139 ops/ms
# Warmup Iteration   2: 2.885 ops/ms
# Warmup Iteration   3: 5.918 ops/ms
Iteration   1: 5.680 ops/ms
Iteration   2: 6.069 ops/ms
Iteration   3: 6.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.974 ±(99.9%) 4.734 ops/ms [Average]
  (min, avg, max) = (5.680, 5.974, 6.172), stdev = 0.259
  CI (99.9%): [1.240, 10.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.818 ops/ms
# Warmup Iteration   2: 5.456 ops/ms
# Warmup Iteration   3: 6.120 ops/ms
Iteration   1: 6.372 ops/ms
Iteration   2: 6.583 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.466 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (6.372, 6.466, 6.583), stdev = 0.107
  CI (99.9%): [4.510, 8.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.618 ops/ms
# Warmup Iteration   2: 5.266 ops/ms
# Warmup Iteration   3: 6.136 ops/ms
Iteration   1: 6.188 ops/ms
Iteration   2: 6.021 ops/ms
Iteration   3: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.190 ±(99.9%) 3.096 ops/ms [Average]
  (min, avg, max) = (6.021, 6.190, 6.360), stdev = 0.170
  CI (99.9%): [3.094, 9.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
# Warmup Iteration   2: 4.356 ops/ms
# Warmup Iteration   3: 5.211 ops/ms
Iteration   1: 5.387 ops/ms
Iteration   2: 5.227 ops/ms
Iteration   3: 5.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.340 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (5.227, 5.340, 5.407), stdev = 0.098
  CI (99.9%): [3.544, 7.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 15.849 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.178 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.259 ±(99.9%) 0.016 ms/op
Iteration   1: 5.039 ±(99.9%) 0.012 ms/op
Iteration   2: 5.158 ±(99.9%) 0.013 ms/op
Iteration   3: 5.088 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.095 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (5.039, 5.095, 5.158), stdev = 0.060
  CI (99.9%): [4.004, 6.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.201 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.198 ±(99.9%) 0.008 ms/op
Iteration   1: 4.977 ±(99.9%) 0.009 ms/op
Iteration   2: 4.953 ±(99.9%) 0.010 ms/op
Iteration   3: 4.981 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.970 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (4.953, 4.970, 4.981), stdev = 0.015
  CI (99.9%): [4.695, 5.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.141 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.985 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.010 ms/op
Iteration   1: 5.455 ±(99.9%) 0.008 ms/op
Iteration   2: 5.192 ±(99.9%) 0.011 ms/op
Iteration   3: 5.274 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.307 ±(99.9%) 2.450 ms/op [Average]
  (min, avg, max) = (5.192, 5.307, 5.455), stdev = 0.134
  CI (99.9%): [2.857, 7.757] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.898 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 7.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.074 ±(99.9%) 0.014 ms/op
Iteration   1: 6.054 ±(99.9%) 0.009 ms/op
Iteration   2: 5.677 ±(99.9%) 0.011 ms/op
Iteration   3: 6.009 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.913 ±(99.9%) 3.759 ms/op [Average]
  (min, avg, max) = (5.677, 5.913, 6.054), stdev = 0.206
  CI (99.9%): [2.154, 9.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.814 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.709 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.024 ms/op
Iteration   1: 5.243 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.154 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.942 ms/op
                 createUser·p0.999:  20.250 ms/op
                 createUser·p0.9999: 25.844 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 5.318 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   11.334 ms/op
                 createUser·p0.999:  22.046 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 5.212 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  25.538 ms/op
                 createUser·p0.9999: 29.749 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182526
  mean =      5.257 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 97346 
    [ 5.000,  7.500) = 75432 
    [ 7.500, 10.000) = 7011 
    [10.000, 12.500) = 1792 
    [12.500, 15.000) = 532 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     28.492 ms/op
     p(99.9990) =     30.120 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.692 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.337 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.035 ±(99.9%) 0.017 ms/op
Iteration   1: 5.133 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.569 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  21.503 ms/op
                 existUser·p0.9999: 26.078 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 5.013 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.775 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  23.340 ms/op
                 existUser·p0.9999: 27.501 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 5.162 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  24.707 ms/op
                 existUser·p0.9999: 28.731 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188062
  mean =      5.102 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 118049 
    [ 5.000,  7.500) = 61813 
    [ 7.500, 10.000) = 5548 
    [10.000, 12.500) = 1489 
    [12.500, 15.000) = 715 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =     10.803 ms/op
     p(99.9000) =     21.723 ms/op
     p(99.9900) =     27.590 ms/op
     p(99.9990) =     29.281 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.945 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.095 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.018 ms/op
Iteration   1: 5.501 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   8.069 ms/op
                 getUser·p0.99:   12.354 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 25.522 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   2: 5.299 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  25.100 ms/op
                 getUser·p0.9999: 28.730 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 5.109 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  25.299 ms/op
                 getUser·p0.9999: 29.302 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181118
  mean =      5.298 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 91175 
    [ 5.000,  7.500) = 80102 
    [ 7.500, 10.000) = 7394 
    [10.000, 12.500) = 1359 
    [12.500, 15.000) = 652 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.859 ms/op
     p(99.9000) =     23.753 ms/op
     p(99.9900) =     28.734 ms/op
     p(99.9990) =     29.850 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.807 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.390 ±(99.9%) 0.025 ms/op
Iteration   1: 6.059 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.654 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   11.435 ms/op
                 listUser·p0.999:  28.265 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   2: 6.156 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  26.179 ms/op
                 listUser·p0.9999: 28.469 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   3: 6.111 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  21.780 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157148
  mean =      6.108 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 11911 
    [ 5.000,  7.500) = 132385 
    [ 7.500, 10.000) = 9436 
    [10.000, 12.500) = 2078 
    [12.500, 15.000) = 640 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     24.894 ms/op
     p(99.9900) =     33.442 ms/op
     p(99.9990) =     36.457 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.974 ± 4.734  ops/ms
ClientPb.existUser                       thrpt       3   6.466 ± 1.957  ops/ms
ClientPb.getUser                         thrpt       3   6.190 ± 3.096  ops/ms
ClientPb.listUser                        thrpt       3   5.340 ± 1.797  ops/ms
ClientPb.createUser                       avgt       3   5.095 ± 1.091   ms/op
ClientPb.existUser                        avgt       3   4.970 ± 0.276   ms/op
ClientPb.getUser                          avgt       3   5.307 ± 2.450   ms/op
ClientPb.listUser                         avgt       3   5.913 ± 3.759   ms/op
ClientPb.createUser                     sample  182526   5.257 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  188062   5.102 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.803           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.723           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.590           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  181118   5.298 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.739           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.859           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.753           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.734           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.983           ms/op
ClientPb.listUser                       sample  157148   6.108 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.442           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
