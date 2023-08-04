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
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.464 ops/ms
# Warmup Iteration   3: 8.568 ops/ms
Iteration   1: 9.059 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.261 ±(99.9%) 3.746 ops/ms [Average]
  (min, avg, max) = (9.059, 9.261, 9.469), stdev = 0.205
  CI (99.9%): [5.515, 13.007] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 9.860 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 9.761 ops/ms
Iteration   3: 9.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.785 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (9.714, 9.785, 9.879), stdev = 0.085
  CI (99.9%): [8.234, 11.335] (assumes normal distribution)


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
# Warmup Iteration   1: 2.963 ops/ms
# Warmup Iteration   2: 8.446 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 9.288 ops/ms
Iteration   2: 9.158 ops/ms
Iteration   3: 9.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.208 ±(99.9%) 1.285 ops/ms [Average]
  (min, avg, max) = (9.158, 9.208, 9.288), stdev = 0.070
  CI (99.9%): [7.923, 10.492] (assumes normal distribution)


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
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 7.742 ops/ms
Iteration   1: 8.062 ops/ms
Iteration   2: 7.790 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.991 ±(99.9%) 3.214 ops/ms [Average]
  (min, avg, max) = (7.790, 7.991, 8.120), stdev = 0.176
  CI (99.9%): [4.776, 11.205] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.980 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.006 ms/op
Iteration   1: 3.539 ±(99.9%) 0.010 ms/op
Iteration   2: 3.472 ±(99.9%) 0.006 ms/op
Iteration   3: 3.429 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.480 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.429, 3.480, 3.539), stdev = 0.055
  CI (99.9%): [2.471, 4.489] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.153 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.006 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
Iteration   3: 3.339 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (3.245, 3.276, 3.339), stdev = 0.054
  CI (99.9%): [2.291, 4.262] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.174 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.005 ms/op
Iteration   1: 3.513 ±(99.9%) 0.007 ms/op
Iteration   2: 3.359 ±(99.9%) 0.008 ms/op
Iteration   3: 3.421 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.359, 3.431, 3.513), stdev = 0.078
  CI (99.9%): [2.015, 4.847] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.339 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.009 ms/op
Iteration   1: 4.051 ±(99.9%) 0.013 ms/op
Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
Iteration   3: 4.155 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.065 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (3.987, 4.065, 4.155), stdev = 0.085
  CI (99.9%): [2.514, 5.615] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.226 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.013 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  20.645 ms/op
                 createUser·p0.9999: 24.026 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.433 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  21.917 ms/op
                 createUser·p0.9999: 31.185 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 3.436 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  22.543 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279163
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10473 
    [ 2.500,  5.000) = 259447 
    [ 5.000,  7.500) = 7621 
    [ 7.500, 10.000) = 1048 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     20.895 ms/op
     p(99.9900) =     30.248 ms/op
     p(99.9990) =     31.722 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.009 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.743 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 23.257 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  21.415 ms/op
                 existUser·p0.9999: 26.951 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.436 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  18.606 ms/op
                 existUser·p0.9999: 27.450 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284549
  mean =      3.371 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11097 
    [ 2.500,  5.000) = 265036 
    [ 5.000,  7.500) = 6641 
    [ 7.500, 10.000) = 1269 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     26.560 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.688 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.013 ms/op
Iteration   1: 3.477 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  20.775 ms/op
                 getUser·p0.9999: 22.591 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.384 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  22.370 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 3.482 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.520 ms/op
                 getUser·p0.999:  20.781 ms/op
                 getUser·p0.9999: 34.553 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278425
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13155 
    [ 2.500,  5.000) = 256148 
    [ 5.000,  7.500) = 7413 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     33.527 ms/op
     p(99.9990) =     35.469 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 10.271 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 4.137 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  19.463 ms/op
                 listUser·p0.9999: 23.667 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  15.823 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.887 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238751
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 228499 
    [ 5.000,  7.500) = 7261 
    [ 7.500, 10.000) = 2049 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.365 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     22.155 ms/op
     p(99.9990) =     24.683 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.261 ± 3.746  ops/ms
ClientPb.existUser                       thrpt       3   9.785 ± 1.551  ops/ms
ClientPb.getUser                         thrpt       3   9.208 ± 1.285  ops/ms
ClientPb.listUser                        thrpt       3   7.991 ± 3.214  ops/ms
ClientPb.createUser                       avgt       3   3.480 ± 1.009   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 0.985   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 1.416   ms/op
ClientPb.listUser                         avgt       3   4.065 ± 1.551   ms/op
ClientPb.createUser                     sample  279163   3.437 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.734           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.145           ms/op
ClientPb.existUser                      sample  284549   3.371 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.030           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.717           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.560           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.901           ms/op
ClientPb.getUser                        sample  278425   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.446           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.527           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.241           ms/op
ClientPb.listUser                       sample  238751   4.017 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.886           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.365           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.794           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.155           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.199           ms/op
