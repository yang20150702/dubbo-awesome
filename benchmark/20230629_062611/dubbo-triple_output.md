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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 5.264 ops/ms
# Warmup Iteration   3: 8.383 ops/ms
Iteration   1: 9.280 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.267 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (9.173, 9.267, 9.348), stdev = 0.088
  CI (99.9%): [7.653, 10.881] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 10.119 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.059 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (9.945, 10.059, 10.119), stdev = 0.099
  CI (99.9%): [8.258, 11.860] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.920 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.415 ops/ms
Iteration   2: 9.187 ops/ms
Iteration   3: 9.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.230 ±(99.9%) 3.066 ops/ms [Average]
  (min, avg, max) = (9.087, 9.230, 9.415), stdev = 0.168
  CI (99.9%): [6.164, 12.296] (assumes normal distribution)


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
# Warmup Iteration   1: 2.449 ops/ms
# Warmup Iteration   2: 6.793 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.996 ±(99.9%) 1.976 ops/ms [Average]
  (min, avg, max) = (7.909, 7.996, 8.117), stdev = 0.108
  CI (99.9%): [6.019, 9.972] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.907 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.003 ms/op
Iteration   1: 3.397 ±(99.9%) 0.007 ms/op
Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
Iteration   3: 3.376 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.378 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.360, 3.378, 3.397), stdev = 0.018
  CI (99.9%): [3.040, 3.715] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.342 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.006 ms/op
Iteration   1: 3.360 ±(99.9%) 0.007 ms/op
Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
Iteration   3: 3.263 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.263, 3.332, 3.374), stdev = 0.060
  CI (99.9%): [2.235, 4.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.541 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.004 ms/op
Iteration   1: 3.393 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.008 ms/op
Iteration   3: 3.453 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.393 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (3.333, 3.393, 3.453), stdev = 0.060
  CI (99.9%): [2.300, 4.486] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.987 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.007 ms/op
Iteration   1: 4.011 ±(99.9%) 0.012 ms/op
Iteration   2: 4.103 ±(99.9%) 0.011 ms/op
Iteration   3: 4.052 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.055 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (4.011, 4.055, 4.103), stdev = 0.046
  CI (99.9%): [3.217, 4.893] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.931 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.010 ms/op
Iteration   1: 3.511 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.069 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.473 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  22.313 ms/op
                 createUser·p0.9999: 25.178 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.444 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  21.670 ms/op
                 createUser·p0.9999: 32.005 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275923
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6017 
    [ 2.500,  5.000) = 261690 
    [ 5.000,  7.500) = 7085 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     30.193 ms/op
     p(99.9990) =     32.529 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.651 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.007 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  19.089 ms/op
                 existUser·p0.9999: 22.586 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  22.008 ms/op
                 existUser·p0.9999: 26.068 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.313 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.712 ms/op
                 existUser·p0.999:  13.259 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286812
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14861 
    [ 2.500,  5.000) = 266384 
    [ 5.000,  7.500) = 4614 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     19.245 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.336 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  11.506 ms/op
                 getUser·p0.9999: 23.134 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  23.084 ms/op
                 getUser·p0.9999: 28.223 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  20.338 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280122
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1932 
    [ 2.500,  5.000) = 269783 
    [ 5.000,  7.500) = 7096 
    [ 7.500, 10.000) = 889 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     11.621 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     34.235 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.424 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.014 ms/op
Iteration   1: 4.103 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  21.398 ms/op
                 listUser·p0.9999: 24.655 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 3.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.824 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.999 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 15.204 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239923
  mean =      4.001 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 230796 
    [ 5.000,  7.500) = 6847 
    [ 7.500, 10.000) = 1353 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     23.823 ms/op
     p(99.9990) =     25.474 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.267 ± 1.614  ops/ms
ClientPb.existUser                       thrpt       3  10.059 ± 1.801  ops/ms
ClientPb.getUser                         thrpt       3   9.230 ± 3.066  ops/ms
ClientPb.listUser                        thrpt       3   7.996 ± 1.976  ops/ms
ClientPb.createUser                       avgt       3   3.378 ± 0.337   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 1.097   ms/op
ClientPb.getUser                          avgt       3   3.393 ± 1.093   ms/op
ClientPb.listUser                         avgt       3   4.055 ± 0.838   ms/op
ClientPb.createUser                     sample  275923   3.475 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.981           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  286812   3.347 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.143           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.245           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  280122   3.426 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.621           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.030           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  239923   4.001 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.266           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.991           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.823           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.985           ms/op
