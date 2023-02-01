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
# Warmup Iteration   1: 0.963 ops/ms
# Warmup Iteration   2: 2.132 ops/ms
# Warmup Iteration   3: 4.919 ops/ms
Iteration   1: 5.130 ops/ms
Iteration   2: 5.479 ops/ms
Iteration   3: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.411 ±(99.9%) 4.642 ops/ms [Average]
  (min, avg, max) = (5.130, 5.411, 5.625), stdev = 0.254
  CI (99.9%): [0.769, 10.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 4.646 ops/ms
# Warmup Iteration   3: 5.373 ops/ms
Iteration   1: 5.750 ops/ms
Iteration   2: 6.069 ops/ms
Iteration   3: 5.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.882 ±(99.9%) 3.036 ops/ms [Average]
  (min, avg, max) = (5.750, 5.882, 6.069), stdev = 0.166
  CI (99.9%): [2.845, 8.918] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.500 ops/ms
# Warmup Iteration   2: 4.352 ops/ms
# Warmup Iteration   3: 5.411 ops/ms
Iteration   1: 5.425 ops/ms
Iteration   2: 5.339 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.509 ±(99.9%) 4.082 ops/ms [Average]
  (min, avg, max) = (5.339, 5.509, 5.762), stdev = 0.224
  CI (99.9%): [1.426, 9.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 3.836 ops/ms
# Warmup Iteration   3: 4.808 ops/ms
Iteration   1: 4.569 ops/ms
Iteration   2: 4.912 ops/ms
Iteration   3: 4.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.724 ±(99.9%) 3.173 ops/ms [Average]
  (min, avg, max) = (4.569, 4.724, 4.912), stdev = 0.174
  CI (99.9%): [1.551, 7.896] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.259 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.822 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.421 ±(99.9%) 0.018 ms/op
Iteration   1: 5.702 ±(99.9%) 0.014 ms/op
Iteration   2: 5.544 ±(99.9%) 0.014 ms/op
Iteration   3: 5.799 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.682 ±(99.9%) 2.347 ms/op [Average]
  (min, avg, max) = (5.544, 5.682, 5.799), stdev = 0.129
  CI (99.9%): [3.335, 8.028] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 18.801 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.795 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.662 ±(99.9%) 0.011 ms/op
Iteration   1: 5.571 ±(99.9%) 0.010 ms/op
Iteration   2: 5.934 ±(99.9%) 0.008 ms/op
Iteration   3: 5.525 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.676 ±(99.9%) 4.087 ms/op [Average]
  (min, avg, max) = (5.525, 5.676, 5.934), stdev = 0.224
  CI (99.9%): [1.589, 9.764] (assumes normal distribution)


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
# Warmup Iteration   1: 18.255 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.810 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.006 ±(99.9%) 0.007 ms/op
Iteration   1: 5.943 ±(99.9%) 0.010 ms/op
Iteration   2: 5.724 ±(99.9%) 0.013 ms/op
Iteration   3: 5.781 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.816 ±(99.9%) 2.075 ms/op [Average]
  (min, avg, max) = (5.724, 5.816, 5.943), stdev = 0.114
  CI (99.9%): [3.741, 7.892] (assumes normal distribution)


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
# Warmup Iteration   1: 19.987 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.879 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.917 ±(99.9%) 0.009 ms/op
Iteration   1: 6.699 ±(99.9%) 0.012 ms/op
Iteration   2: 6.460 ±(99.9%) 0.017 ms/op
Iteration   3: 6.885 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.681 ±(99.9%) 3.883 ms/op [Average]
  (min, avg, max) = (6.460, 6.681, 6.885), stdev = 0.213
  CI (99.9%): [2.798, 10.564] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 20.373 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 8.528 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.381 ±(99.9%) 0.029 ms/op
Iteration   1: 5.901 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.605 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.525 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  27.691 ms/op
                 createUser·p0.9999: 36.372 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   2: 6.131 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.710 ms/op
                 createUser·p0.90:   7.823 ms/op
                 createUser·p0.95:   9.126 ms/op
                 createUser·p0.99:   12.943 ms/op
                 createUser·p0.999:  28.075 ms/op
                 createUser·p0.9999: 31.778 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   3: 5.944 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.470 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.537 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  28.953 ms/op
                 createUser·p0.9999: 32.788 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160258
  mean =      5.990 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 33152 
    [ 5.000,  7.500) = 110329 
    [ 7.500, 10.000) = 13121 
    [10.000, 12.500) = 2525 
    [12.500, 15.000) = 639 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     28.082 ms/op
     p(99.9900) =     34.798 ms/op
     p(99.9990) =     37.119 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.075 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.069 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.808 ±(99.9%) 0.019 ms/op
Iteration   1: 5.521 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.302 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   8.348 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  23.957 ms/op
                 existUser·p0.9999: 26.392 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 5.784 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   5.415 ms/op
                 existUser·p0.90:   7.422 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   12.075 ms/op
                 existUser·p0.999:  31.468 ms/op
                 existUser·p0.9999: 34.944 ms/op
                 existUser·p1.00:   39.649 ms/op

Iteration   3: 5.657 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   7.447 ms/op
                 existUser·p0.95:   8.667 ms/op
                 existUser·p0.99:   11.895 ms/op
                 existUser·p0.999:  16.893 ms/op
                 existUser·p0.9999: 29.830 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169696
  mean =      5.652 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 61752 
    [ 5.000,  7.500) = 92739 
    [ 7.500, 10.000) = 11547 
    [10.000, 12.500) = 2420 
    [12.500, 15.000) = 822 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.748 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     37.274 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 20.340 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.318 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.156 ±(99.9%) 0.028 ms/op
Iteration   1: 6.036 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.638 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   13.074 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 30.997 ms/op
                 getUser·p1.00:   32.637 ms/op

Iteration   2: 5.835 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.277 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   11.514 ms/op
                 getUser·p0.999:  29.032 ms/op
                 getUser·p0.9999: 38.666 ms/op
                 getUser·p1.00:   38.666 ms/op

Iteration   3: 5.656 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  26.361 ms/op
                 getUser·p0.9999: 30.813 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164252
  mean =      5.838 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 46042 
    [ 5.000,  7.500) = 101822 
    [ 7.500, 10.000) = 12019 
    [10.000, 12.500) = 2908 
    [12.500, 15.000) = 907 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     26.370 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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
# Warmup Iteration   1: 20.772 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 8.438 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 7.004 ±(99.9%) 0.030 ms/op
Iteration   1: 6.679 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.167 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.845 ms/op
                 listUser·p0.999:  28.713 ms/op
                 listUser·p0.9999: 32.566 ms/op
                 listUser·p1.00:   33.194 ms/op

Iteration   2: 6.698 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.633 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.870 ms/op
                 listUser·p0.999:  29.294 ms/op
                 listUser·p0.9999: 34.093 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   3: 6.667 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   12.327 ms/op
                 listUser·p0.999:  26.184 ms/op
                 listUser·p0.9999: 30.739 ms/op
                 listUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143592
  mean =      6.682 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3974 
    [ 5.000,  7.500) = 115330 
    [ 7.500, 10.000) = 19484 
    [10.000, 12.500) = 3440 
    [12.500, 15.000) = 778 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      6.332 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.257 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     27.899 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     37.369 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.411 ± 4.642  ops/ms
ClientPb.existUser                       thrpt       3   5.882 ± 3.036  ops/ms
ClientPb.getUser                         thrpt       3   5.509 ± 4.082  ops/ms
ClientPb.listUser                        thrpt       3   4.724 ± 3.173  ops/ms
ClientPb.createUser                       avgt       3   5.682 ± 2.347   ms/op
ClientPb.existUser                        avgt       3   5.676 ± 4.087   ms/op
ClientPb.getUser                          avgt       3   5.816 ± 2.075   ms/op
ClientPb.listUser                         avgt       3   6.681 ± 3.883   ms/op
ClientPb.createUser                     sample  160258   5.990 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.684           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.682           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.798           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  169696   5.652 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.536           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.055           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.620           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.649           ms/op
ClientPb.getUser                        sample  164252   5.838 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.277           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.288           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.370           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.470           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.666           ms/op
ClientPb.listUser                       sample  143592   6.682 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.138           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.332           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.899           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.801           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.683           ms/op
