# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.023 ops/ms
# Warmup Iteration   2: 2.278 ops/ms
# Warmup Iteration   3: 4.868 ops/ms
Iteration   1: 5.393 ops/ms
Iteration   2: 5.630 ops/ms
Iteration   3: 5.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.658 ±(99.9%) 5.095 ops/ms [Average]
  (min, avg, max) = (5.393, 5.658, 5.950), stdev = 0.279
  CI (99.9%): [0.562, 10.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.681 ops/ms
# Warmup Iteration   2: 4.576 ops/ms
# Warmup Iteration   3: 5.546 ops/ms
Iteration   1: 6.009 ops/ms
Iteration   2: 5.986 ops/ms
Iteration   3: 6.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.021 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (5.986, 6.021, 6.068), stdev = 0.042
  CI (99.9%): [5.250, 6.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.524 ops/ms
# Warmup Iteration   2: 4.052 ops/ms
# Warmup Iteration   3: 5.712 ops/ms
Iteration   1: 5.750 ops/ms
Iteration   2: 5.799 ops/ms
Iteration   3: 5.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.795 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (5.750, 5.795, 5.837), stdev = 0.044
  CI (99.9%): [4.995, 6.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.580 ops/ms
# Warmup Iteration   2: 3.788 ops/ms
# Warmup Iteration   3: 4.806 ops/ms
Iteration   1: 4.882 ops/ms
Iteration   2: 5.166 ops/ms
Iteration   3: 5.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.060 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (4.882, 5.060, 5.166), stdev = 0.155
  CI (99.9%): [2.231, 7.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.160 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.807 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.576 ±(99.9%) 0.007 ms/op
Iteration   1: 5.954 ±(99.9%) 0.011 ms/op
Iteration   2: 5.741 ±(99.9%) 0.014 ms/op
Iteration   3: 5.593 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.763 ±(99.9%) 3.309 ms/op [Average]
  (min, avg, max) = (5.593, 5.763, 5.954), stdev = 0.181
  CI (99.9%): [2.454, 9.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.830 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.359 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.011 ms/op
Iteration   1: 5.020 ±(99.9%) 0.011 ms/op
Iteration   2: 4.989 ±(99.9%) 0.016 ms/op
Iteration   3: 5.229 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.079 ±(99.9%) 2.384 ms/op [Average]
  (min, avg, max) = (4.989, 5.079, 5.229), stdev = 0.131
  CI (99.9%): [2.695, 7.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.992 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.665 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.594 ±(99.9%) 0.011 ms/op
Iteration   1: 5.576 ±(99.9%) 0.012 ms/op
Iteration   2: 5.347 ±(99.9%) 0.018 ms/op
Iteration   3: 5.369 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.431 ±(99.9%) 2.298 ms/op [Average]
  (min, avg, max) = (5.347, 5.431, 5.576), stdev = 0.126
  CI (99.9%): [3.132, 7.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.253 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 8.149 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.706 ±(99.9%) 0.011 ms/op
Iteration   1: 6.606 ±(99.9%) 0.013 ms/op
Iteration   2: 6.253 ±(99.9%) 0.018 ms/op
Iteration   3: 6.106 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.322 ±(99.9%) 4.691 ms/op [Average]
  (min, avg, max) = (6.106, 6.322, 6.606), stdev = 0.257
  CI (99.9%): [1.630, 11.013] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 17.301 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.991 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.824 ±(99.9%) 0.027 ms/op
Iteration   1: 5.521 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  24.321 ms/op
                 createUser·p0.9999: 27.080 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   2: 5.301 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  25.517 ms/op
                 createUser·p0.9999: 36.236 ms/op
                 createUser·p1.00:   38.732 ms/op

Iteration   3: 5.383 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  29.121 ms/op
                 createUser·p0.9999: 34.082 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177728
  mean =      5.400 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 72159 
    [ 5.000,  7.500) = 97258 
    [ 7.500, 10.000) = 6297 
    [10.000, 12.500) = 1286 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     24.635 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     37.051 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.563 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.915 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.248 ±(99.9%) 0.019 ms/op
Iteration   1: 5.214 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.383 ms/op
                 existUser·p0.99:   10.310 ms/op
                 existUser·p0.999:  23.101 ms/op
                 existUser·p0.9999: 27.201 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 5.232 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   10.862 ms/op
                 existUser·p0.999:  27.060 ms/op
                 existUser·p0.9999: 29.295 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   3: 5.155 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.888 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  16.499 ms/op
                 existUser·p0.9999: 30.229 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184443
  mean =      5.200 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 99866 
    [ 5.000,  7.500) = 76771 
    [ 7.500, 10.000) = 5581 
    [10.000, 12.500) = 1433 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     29.313 ms/op
     p(99.9990) =     31.052 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.775 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 6.978 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.019 ms/op
Iteration   1: 5.620 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   8.192 ms/op
                 getUser·p0.99:   11.370 ms/op
                 getUser·p0.999:  22.710 ms/op
                 getUser·p0.9999: 26.081 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 5.355 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   7.070 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  18.638 ms/op
                 getUser·p0.9999: 26.561 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 5.496 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.560 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   10.561 ms/op
                 getUser·p0.999:  26.055 ms/op
                 getUser·p0.9999: 29.803 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174910
  mean =      5.489 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63820 
    [ 5.000,  7.500) = 101909 
    [ 7.500, 10.000) = 6450 
    [10.000, 12.500) = 1800 
    [12.500, 15.000) = 585 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.560 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     22.547 ms/op
     p(99.9900) =     29.246 ms/op
     p(99.9990) =     30.443 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.204 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.715 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.546 ±(99.9%) 0.027 ms/op
Iteration   1: 6.327 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.338 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  28.148 ms/op
                 listUser·p0.9999: 32.369 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   2: 6.321 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.031 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.996 ms/op
                 listUser·p0.999:  30.474 ms/op
                 listUser·p0.9999: 35.380 ms/op
                 listUser·p1.00:   35.914 ms/op

Iteration   3: 6.452 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.418 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  23.466 ms/op
                 listUser·p0.9999: 28.372 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150641
  mean =      6.366 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5021 
    [ 5.000,  7.500) = 132648 
    [ 7.500, 10.000) = 9517 
    [10.000, 12.500) = 2320 
    [12.500, 15.000) = 607 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     28.106 ms/op
     p(99.9900) =     33.494 ms/op
     p(99.9990) =     35.847 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.658 ± 5.095  ops/ms
ClientPb.existUser                       thrpt       3   6.021 ± 0.771  ops/ms
ClientPb.getUser                         thrpt       3   5.795 ± 0.801  ops/ms
ClientPb.listUser                        thrpt       3   5.060 ± 2.828  ops/ms
ClientPb.createUser                       avgt       3   5.763 ± 3.309   ms/op
ClientPb.existUser                        avgt       3   5.079 ± 2.384   ms/op
ClientPb.getUser                          avgt       3   5.431 ± 2.298   ms/op
ClientPb.listUser                         avgt       3   6.322 ± 4.691   ms/op
ClientPb.createUser                     sample  177728   5.400 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.635           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.865           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.732           ms/op
ClientPb.existUser                      sample  184443   5.200 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.645           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.225           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.469           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.007           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.162           ms/op
ClientPb.getUser                        sample  174910   5.489 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.547           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.719           ms/op
ClientPb.listUser                       sample  150641   6.366 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.989           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.258           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.633           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.106           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.494           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.914           ms/op
