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
# Warmup Iteration   1: 0.984 ops/ms
# Warmup Iteration   2: 2.227 ops/ms
# Warmup Iteration   3: 4.953 ops/ms
Iteration   1: 5.535 ops/ms
Iteration   2: 5.810 ops/ms
Iteration   3: 6.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.861 ±(99.9%) 6.478 ops/ms [Average]
  (min, avg, max) = (5.535, 5.861, 6.239), stdev = 0.355
  CI (99.9%): [≈ 0, 12.339] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 5.396 ops/ms
# Warmup Iteration   3: 6.080 ops/ms
Iteration   1: 6.346 ops/ms
Iteration   2: 6.167 ops/ms
Iteration   3: 6.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.299 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (6.167, 6.299, 6.384), stdev = 0.116
  CI (99.9%): [4.189, 8.409] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.392 ops/ms
# Warmup Iteration   2: 4.152 ops/ms
# Warmup Iteration   3: 5.740 ops/ms
Iteration   1: 5.901 ops/ms
Iteration   2: 5.912 ops/ms
Iteration   3: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.915 ±(99.9%) 0.278 ops/ms [Average]
  (min, avg, max) = (5.901, 5.915, 5.931), stdev = 0.015
  CI (99.9%): [5.636, 6.193] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.326 ops/ms
# Warmup Iteration   2: 3.899 ops/ms
# Warmup Iteration   3: 5.281 ops/ms
Iteration   1: 5.048 ops/ms
Iteration   2: 5.297 ops/ms
Iteration   3: 5.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.205 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (5.048, 5.205, 5.297), stdev = 0.137
  CI (99.9%): [2.713, 7.697] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.146 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 6.698 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.402 ±(99.9%) 0.020 ms/op
Iteration   1: 5.303 ±(99.9%) 0.011 ms/op
Iteration   2: 5.332 ±(99.9%) 0.007 ms/op
Iteration   3: 5.255 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.297 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (5.255, 5.297, 5.332), stdev = 0.039
  CI (99.9%): [4.588, 6.005] (assumes normal distribution)


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
# Warmup Iteration   1: 16.520 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.485 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.195 ±(99.9%) 0.006 ms/op
Iteration   1: 5.074 ±(99.9%) 0.011 ms/op
Iteration   2: 5.057 ±(99.9%) 0.011 ms/op
Iteration   3: 5.113 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.081 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (5.057, 5.081, 5.113), stdev = 0.029
  CI (99.9%): [4.560, 5.603] (assumes normal distribution)


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
# Warmup Iteration   1: 17.651 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.042 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.005 ms/op
Iteration   1: 5.342 ±(99.9%) 0.015 ms/op
Iteration   2: 5.391 ±(99.9%) 0.010 ms/op
Iteration   3: 5.375 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.369 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (5.342, 5.369, 5.391), stdev = 0.025
  CI (99.9%): [4.918, 5.820] (assumes normal distribution)


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
# Warmup Iteration   1: 20.043 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 8.689 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.089 ±(99.9%) 0.024 ms/op
Iteration   1: 6.251 ±(99.9%) 0.019 ms/op
Iteration   2: 6.196 ±(99.9%) 0.015 ms/op
Iteration   3: 6.097 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.182 ±(99.9%) 1.429 ms/op [Average]
  (min, avg, max) = (6.097, 6.182, 6.251), stdev = 0.078
  CI (99.9%): [4.752, 7.611] (assumes normal distribution)


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
# Warmup Iteration   1: 19.873 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 7.130 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.711 ±(99.9%) 0.027 ms/op
Iteration   1: 5.329 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.253 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   11.494 ms/op
                 createUser·p0.999:  21.427 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 5.278 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  25.585 ms/op
                 createUser·p0.9999: 33.421 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 5.508 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  26.973 ms/op
                 createUser·p0.9999: 30.290 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178751
  mean =      5.370 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 85264 
    [ 5.000,  7.500) = 83394 
    [ 7.500, 10.000) = 7502 
    [10.000, 12.500) = 1659 
    [12.500, 15.000) = 599 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     22.830 ms/op
     p(99.9900) =     31.338 ms/op
     p(99.9990) =     34.158 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 17.608 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 5.967 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.289 ±(99.9%) 0.021 ms/op
Iteration   1: 5.214 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  24.302 ms/op
                 existUser·p0.9999: 29.942 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   2: 4.995 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   10.897 ms/op
                 existUser·p0.999:  23.694 ms/op
                 existUser·p0.9999: 27.643 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   3: 5.196 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  17.321 ms/op
                 existUser·p0.9999: 32.491 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186906
  mean =      5.133 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 113514 
    [ 5.000,  7.500) = 64263 
    [ 7.500, 10.000) = 6600 
    [10.000, 12.500) = 1636 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     19.041 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     33.401 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 18.764 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.949 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.022 ms/op
Iteration   1: 5.571 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.029 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  24.710 ms/op
                 getUser·p0.9999: 29.237 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 5.470 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.875 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   12.657 ms/op
                 getUser·p0.999:  25.609 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   43.778 ms/op

Iteration   3: 5.335 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.743 ms/op
                 getUser·p0.999:  22.916 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175835
  mean =      5.457 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78329 
    [ 5.000, 10.000) = 94185 
    [10.000, 15.000) = 2838 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 66 
    [25.000, 30.000) = 162 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.528 ms/op
     p(99.9000) =     24.914 ms/op
     p(99.9900) =     29.374 ms/op
     p(99.9990) =     43.728 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


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
# Warmup Iteration   1: 19.186 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 8.335 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.422 ±(99.9%) 0.032 ms/op
Iteration   1: 6.167 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 27.814 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   2: 6.104 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   13.438 ms/op
                 listUser·p0.999:  29.446 ms/op
                 listUser·p0.9999: 31.384 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   3: 6.081 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.258 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.282 ms/op
                 listUser·p0.999:  21.639 ms/op
                 listUser·p0.9999: 33.406 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156895
  mean =      6.117 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 12812 
    [ 5.000,  7.500) = 129561 
    [ 7.500, 10.000) = 9358 
    [10.000, 12.500) = 3408 
    [12.500, 15.000) = 948 
    [15.000, 17.500) = 384 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.878 ms/op
     p(99.9000) =     26.588 ms/op
     p(99.9900) =     32.766 ms/op
     p(99.9990) =     33.958 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.861 ± 6.478  ops/ms
ClientPb.existUser                       thrpt       3   6.299 ± 2.110  ops/ms
ClientPb.getUser                         thrpt       3   5.915 ± 0.278  ops/ms
ClientPb.listUser                        thrpt       3   5.205 ± 2.492  ops/ms
ClientPb.createUser                       avgt       3   5.297 ± 0.708   ms/op
ClientPb.existUser                        avgt       3   5.081 ± 0.522   ms/op
ClientPb.getUser                          avgt       3   5.369 ± 0.451   ms/op
ClientPb.listUser                         avgt       3   6.182 ± 1.429   ms/op
ClientPb.createUser                     sample  178751   5.370 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.603           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.846           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.338           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  186906   5.133 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.769           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.430           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.605           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  175835   5.457 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.832           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.053           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.914           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.374           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.778           ms/op
ClientPb.listUser                       sample  156895   6.117 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.093           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.878           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.588           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.766           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.144           ms/op
