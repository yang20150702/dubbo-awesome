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
# Warmup Iteration   1: 1.295 ops/ms
# Warmup Iteration   2: 3.070 ops/ms
# Warmup Iteration   3: 5.664 ops/ms
Iteration   1: 6.098 ops/ms
Iteration   2: 6.202 ops/ms
Iteration   3: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.154 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (6.098, 6.154, 6.202), stdev = 0.053
  CI (99.9%): [5.191, 7.116] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.848 ops/ms
# Warmup Iteration   2: 5.109 ops/ms
# Warmup Iteration   3: 6.373 ops/ms
Iteration   1: 6.580 ops/ms
Iteration   2: 6.474 ops/ms
Iteration   3: 6.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.652 ±(99.9%) 4.051 ops/ms [Average]
  (min, avg, max) = (6.474, 6.652, 6.901), stdev = 0.222
  CI (99.9%): [2.601, 10.703] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 5.409 ops/ms
# Warmup Iteration   3: 6.097 ops/ms
Iteration   1: 6.215 ops/ms
Iteration   2: 6.074 ops/ms
Iteration   3: 6.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.118 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (6.064, 6.118, 6.215), stdev = 0.084
  CI (99.9%): [4.583, 7.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.703 ops/ms
# Warmup Iteration   2: 4.415 ops/ms
# Warmup Iteration   3: 5.073 ops/ms
Iteration   1: 4.958 ops/ms
Iteration   2: 4.919 ops/ms
Iteration   3: 5.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.064 ±(99.9%) 3.988 ops/ms [Average]
  (min, avg, max) = (4.919, 5.064, 5.316), stdev = 0.219
  CI (99.9%): [1.076, 9.052] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.962 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.869 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.016 ms/op
Iteration   1: 5.049 ±(99.9%) 0.012 ms/op
Iteration   2: 4.805 ±(99.9%) 0.024 ms/op
Iteration   3: 5.294 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.050 ±(99.9%) 4.463 ms/op [Average]
  (min, avg, max) = (4.805, 5.050, 5.294), stdev = 0.245
  CI (99.9%): [0.587, 9.513] (assumes normal distribution)


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
# Warmup Iteration   1: 15.274 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.867 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.010 ms/op
Iteration   1: 4.848 ±(99.9%) 0.017 ms/op
Iteration   2: 4.840 ±(99.9%) 0.015 ms/op
Iteration   3: 5.057 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.915 ±(99.9%) 2.237 ms/op [Average]
  (min, avg, max) = (4.840, 4.915, 5.057), stdev = 0.123
  CI (99.9%): [2.678, 7.153] (assumes normal distribution)


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
# Warmup Iteration   1: 16.045 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.182 ±(99.9%) 0.012 ms/op
Iteration   1: 5.237 ±(99.9%) 0.012 ms/op
Iteration   2: 5.052 ±(99.9%) 0.016 ms/op
Iteration   3: 5.088 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.126 ±(99.9%) 1.791 ms/op [Average]
  (min, avg, max) = (5.052, 5.126, 5.237), stdev = 0.098
  CI (99.9%): [3.335, 6.917] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.946 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.904 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.080 ±(99.9%) 0.015 ms/op
Iteration   1: 5.869 ±(99.9%) 0.015 ms/op
Iteration   2: 5.836 ±(99.9%) 0.012 ms/op
Iteration   3: 5.969 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.891 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (5.836, 5.891, 5.969), stdev = 0.070
  CI (99.9%): [4.623, 7.160] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.567 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.007 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.541 ±(99.9%) 0.019 ms/op
Iteration   1: 4.827 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.462 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.501 ms/op
                 createUser·p0.999:  16.024 ms/op
                 createUser·p0.9999: 33.305 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   2: 5.264 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  25.782 ms/op
                 createUser·p0.9999: 31.684 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   3: 5.229 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   6.881 ms/op
                 createUser·p0.99:   9.342 ms/op
                 createUser·p0.999:  27.126 ms/op
                 createUser·p0.9999: 30.507 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188124
  mean =      5.099 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 108044 
    [ 5.000,  7.500) = 75379 
    [ 7.500, 10.000) = 3466 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      6.685 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     25.162 ms/op
     p(99.9900) =     32.201 ms/op
     p(99.9990) =     33.910 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.918 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.890 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.378 ±(99.9%) 0.017 ms/op
Iteration   1: 5.216 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   9.188 ms/op
                 existUser·p0.999:  23.290 ms/op
                 existUser·p0.9999: 26.959 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   2: 4.722 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.167 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 26.179 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 5.197 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   6.955 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  25.526 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190684
  mean =      5.035 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 118808 
    [ 5.000,  7.500) = 65826 
    [ 7.500, 10.000) = 4764 
    [10.000, 12.500) = 684 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.776 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     22.953 ms/op
     p(99.9900) =     29.325 ms/op
     p(99.9990) =     31.524 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 15.009 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.171 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.135 ±(99.9%) 0.016 ms/op
Iteration   1: 5.302 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.273 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   10.790 ms/op
                 getUser·p0.999:  24.953 ms/op
                 getUser·p0.9999: 29.554 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   2: 5.399 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.343 ms/op
                 getUser·p0.99:   9.465 ms/op
                 getUser·p0.999:  14.432 ms/op
                 getUser·p0.9999: 27.994 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 5.155 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  26.967 ms/op
                 getUser·p0.9999: 32.080 ms/op
                 getUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181490
  mean =      5.284 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 85203 
    [ 5.000,  7.500) = 89091 
    [ 7.500, 10.000) = 5677 
    [10.000, 12.500) = 923 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     25.150 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     32.444 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 17.987 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.910 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.024 ms/op
Iteration   1: 6.106 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  28.429 ms/op
                 listUser·p0.9999: 42.863 ms/op
                 listUser·p1.00:   48.038 ms/op

Iteration   2: 5.875 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  26.903 ms/op
                 listUser·p0.9999: 31.889 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   3: 6.167 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.709 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  21.762 ms/op
                 listUser·p0.9999: 39.178 ms/op
                 listUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158665
  mean =      6.047 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9430 
    [ 5.000, 10.000) = 146673 
    [10.000, 15.000) = 2184 
    [15.000, 20.000) = 106 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 42 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.808 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.655 ms/op
     p(99.9000) =     26.553 ms/op
     p(99.9900) =     41.174 ms/op
     p(99.9990) =     46.538 ms/op
     p(99.9999) =     48.038 ms/op
    p(100.0000) =     48.038 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.154 ± 0.963  ops/ms
ClientPb.existUser                       thrpt       3   6.652 ± 4.051  ops/ms
ClientPb.getUser                         thrpt       3   6.118 ± 1.535  ops/ms
ClientPb.listUser                        thrpt       3   5.064 ± 3.988  ops/ms
ClientPb.createUser                       avgt       3   5.050 ± 4.463   ms/op
ClientPb.existUser                        avgt       3   4.915 ± 2.237   ms/op
ClientPb.getUser                          avgt       3   5.126 ± 1.791   ms/op
ClientPb.listUser                         avgt       3   5.891 ± 1.269   ms/op
ClientPb.createUser                     sample  188124   5.099 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.847           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  190684   5.035 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.776           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.077           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.953           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.325           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  181490   5.284 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.454           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.507           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  158665   6.047 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.655           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.553           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.038           ms/op
