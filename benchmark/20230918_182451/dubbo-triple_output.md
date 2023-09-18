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
# Warmup Iteration   1: 1.488 ops/ms
# Warmup Iteration   2: 3.027 ops/ms
# Warmup Iteration   3: 6.040 ops/ms
Iteration   1: 6.710 ops/ms
Iteration   2: 7.278 ops/ms
Iteration   3: 7.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.080 ±(99.9%) 5.846 ops/ms [Average]
  (min, avg, max) = (6.710, 7.080, 7.278), stdev = 0.320
  CI (99.9%): [1.234, 12.926] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.802 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 7.321 ops/ms
Iteration   1: 7.760 ops/ms
Iteration   2: 7.589 ops/ms
Iteration   3: 7.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.664 ±(99.9%) 1.595 ops/ms [Average]
  (min, avg, max) = (7.589, 7.664, 7.760), stdev = 0.087
  CI (99.9%): [6.069, 9.258] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.916 ops/ms
# Warmup Iteration   2: 5.664 ops/ms
# Warmup Iteration   3: 7.080 ops/ms
Iteration   1: 7.151 ops/ms
Iteration   2: 7.263 ops/ms
Iteration   3: 7.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.215 ±(99.9%) 1.054 ops/ms [Average]
  (min, avg, max) = (7.151, 7.215, 7.263), stdev = 0.058
  CI (99.9%): [6.161, 8.269] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.023 ops/ms
# Warmup Iteration   3: 5.874 ops/ms
Iteration   1: 5.891 ops/ms
Iteration   2: 6.160 ops/ms
Iteration   3: 6.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.046 ±(99.9%) 2.544 ops/ms [Average]
  (min, avg, max) = (5.891, 6.046, 6.160), stdev = 0.139
  CI (99.9%): [3.502, 8.590] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.152 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.851 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.660 ±(99.9%) 0.005 ms/op
Iteration   1: 4.399 ±(99.9%) 0.009 ms/op
Iteration   2: 4.383 ±(99.9%) 0.006 ms/op
Iteration   3: 4.308 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.364 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (4.308, 4.364, 4.399), stdev = 0.048
  CI (99.9%): [3.479, 5.248] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.902 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.631 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.385 ±(99.9%) 0.007 ms/op
Iteration   1: 4.156 ±(99.9%) 0.005 ms/op
Iteration   2: 4.239 ±(99.9%) 0.005 ms/op
Iteration   3: 4.324 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.240 ±(99.9%) 1.539 ms/op [Average]
  (min, avg, max) = (4.156, 4.240, 4.324), stdev = 0.084
  CI (99.9%): [2.700, 5.779] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 14.579 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.007 ms/op
Iteration   1: 4.359 ±(99.9%) 0.004 ms/op
Iteration   2: 4.346 ±(99.9%) 0.005 ms/op
Iteration   3: 4.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.266 ±(99.9%) 2.743 ms/op [Average]
  (min, avg, max) = (4.092, 4.266, 4.359), stdev = 0.150
  CI (99.9%): [1.523, 7.009] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.578 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.211 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.275 ±(99.9%) 0.007 ms/op
Iteration   1: 4.861 ±(99.9%) 0.009 ms/op
Iteration   2: 5.203 ±(99.9%) 0.010 ms/op
Iteration   3: 5.003 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.022 ±(99.9%) 3.139 ms/op [Average]
  (min, avg, max) = (4.861, 5.022, 5.203), stdev = 0.172
  CI (99.9%): [1.883, 8.162] (assumes normal distribution)


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
# Warmup Iteration   1: 14.240 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 6.115 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.026 ms/op
Iteration   1: 4.502 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   9.512 ms/op
                 createUser·p0.999:  20.214 ms/op
                 createUser·p0.9999: 25.683 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 4.356 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.048 ms/op
                 createUser·p0.50:   4.153 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  13.787 ms/op
                 createUser·p0.9999: 32.843 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   3: 4.546 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  30.573 ms/op
                 createUser·p0.9999: 35.221 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 215029
  mean =      4.467 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 185625 
    [ 5.000,  7.500) = 24382 
    [ 7.500, 10.000) = 3529 
    [10.000, 12.500) = 915 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     25.264 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.152 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 4.973 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.016 ms/op
Iteration   1: 4.111 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  16.056 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 4.333 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  15.663 ms/op
                 existUser·p0.9999: 42.315 ms/op
                 existUser·p1.00:   42.598 ms/op

Iteration   3: 4.329 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.958 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   10.065 ms/op
                 existUser·p0.999:  18.518 ms/op
                 existUser·p0.9999: 31.740 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 225622
  mean =      4.255 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 202765 
    [ 5.000, 10.000) = 21290 
    [10.000, 15.000) = 1262 
    [15.000, 20.000) = 111 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     41.484 ms/op
     p(99.9990) =     42.598 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.948 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.437 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.630 ±(99.9%) 0.018 ms/op
Iteration   1: 4.452 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  15.846 ms/op
                 getUser·p0.9999: 26.622 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 4.292 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 27.955 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 4.384 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  25.857 ms/op
                 getUser·p0.9999: 29.524 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 219156
  mean =      4.375 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 199338 
    [ 5.000,  7.500) = 15775 
    [ 7.500, 10.000) = 2653 
    [10.000, 12.500) = 825 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 129 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     23.293 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     30.140 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 17.602 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 6.603 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.022 ms/op
Iteration   1: 5.252 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   7.377 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  27.037 ms/op
                 listUser·p0.9999: 32.533 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 5.206 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  24.117 ms/op
                 listUser·p0.9999: 28.176 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   3: 5.075 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.130 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 185334
  mean =      5.176 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 107947 
    [ 5.000,  7.500) = 69064 
    [ 7.500, 10.000) = 5911 
    [10.000, 12.500) = 1381 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      7.186 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     24.423 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     33.379 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.080 ± 5.846  ops/ms
ClientPb.existUser                       thrpt       3   7.664 ± 1.595  ops/ms
ClientPb.getUser                         thrpt       3   7.215 ± 1.054  ops/ms
ClientPb.listUser                        thrpt       3   6.046 ± 2.544  ops/ms
ClientPb.createUser                       avgt       3   4.364 ± 0.885   ms/op
ClientPb.existUser                        avgt       3   4.240 ± 1.539   ms/op
ClientPb.getUser                          avgt       3   4.266 ± 2.743   ms/op
ClientPb.listUser                         avgt       3   5.022 ± 3.139   ms/op
ClientPb.createUser                     sample  215029   4.467 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.624           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.111           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.044           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  225622   4.255 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.022           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.110           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.598           ms/op
ClientPb.getUser                        sample  219156   4.375 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.716           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.293           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  185334   5.176 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.003           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.186           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.423           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.064           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
