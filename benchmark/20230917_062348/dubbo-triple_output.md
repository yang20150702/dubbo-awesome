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
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 3.449 ops/ms
# Warmup Iteration   3: 7.309 ops/ms
Iteration   1: 7.300 ops/ms
Iteration   2: 7.882 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.786 ±(99.9%) 8.128 ops/ms [Average]
  (min, avg, max) = (7.300, 7.786, 8.175), stdev = 0.446
  CI (99.9%): [≈ 0, 15.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 6.905 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.201 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (8.151, 8.201, 8.276), stdev = 0.066
  CI (99.9%): [6.990, 9.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 6.182 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.586 ops/ms
Iteration   2: 7.711 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.740 ±(99.9%) 3.118 ops/ms [Average]
  (min, avg, max) = (7.586, 7.740, 7.924), stdev = 0.171
  CI (99.9%): [4.622, 10.858] (assumes normal distribution)


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
# Warmup Iteration   1: 1.836 ops/ms
# Warmup Iteration   2: 4.934 ops/ms
# Warmup Iteration   3: 6.524 ops/ms
Iteration   1: 6.494 ops/ms
Iteration   2: 6.519 ops/ms
Iteration   3: 6.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.527 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (6.494, 6.527, 6.569), stdev = 0.038
  CI (99.9%): [5.835, 7.220] (assumes normal distribution)


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
# Warmup Iteration   1: 12.466 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.004 ms/op
Iteration   1: 4.061 ±(99.9%) 0.004 ms/op
Iteration   2: 3.984 ±(99.9%) 0.005 ms/op
Iteration   3: 4.244 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.096 ±(99.9%) 2.439 ms/op [Average]
  (min, avg, max) = (3.984, 4.096, 4.244), stdev = 0.134
  CI (99.9%): [1.658, 6.535] (assumes normal distribution)


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
# Warmup Iteration   1: 11.452 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.004 ms/op
Iteration   1: 3.909 ±(99.9%) 0.004 ms/op
Iteration   2: 3.890 ±(99.9%) 0.003 ms/op
Iteration   3: 3.859 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.886 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.859, 3.886, 3.909), stdev = 0.025
  CI (99.9%): [3.429, 4.343] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.458 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.005 ms/op
Iteration   1: 4.253 ±(99.9%) 0.007 ms/op
Iteration   2: 4.132 ±(99.9%) 0.005 ms/op
Iteration   3: 4.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.137 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (4.025, 4.137, 4.253), stdev = 0.114
  CI (99.9%): [2.054, 6.219] (assumes normal distribution)


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
# Warmup Iteration   1: 15.205 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.041 ±(99.9%) 0.007 ms/op
Iteration   1: 4.919 ±(99.9%) 0.011 ms/op
Iteration   2: 4.847 ±(99.9%) 0.011 ms/op
Iteration   3: 4.890 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.885 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (4.847, 4.885, 4.919), stdev = 0.036
  CI (99.9%): [4.226, 5.544] (assumes normal distribution)


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
# Warmup Iteration   1: 12.838 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 5.275 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.869 ±(99.9%) 0.022 ms/op
Iteration   1: 4.214 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   8.249 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 27.965 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 4.126 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  25.577 ms/op
                 createUser·p0.9999: 29.696 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 4.064 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   8.225 ms/op
                 createUser·p0.999:  16.487 ms/op
                 createUser·p0.9999: 53.560 ms/op
                 createUser·p1.00:   60.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232075
  mean =      4.134 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 214335 
    [ 5.000, 10.000) = 16844 
    [10.000, 15.000) = 587 
    [15.000, 20.000) = 83 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 132 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     50.449 ms/op
     p(99.9990) =     57.126 ms/op
     p(99.9999) =     60.359 ms/op
    p(100.0000) =     60.359 ms/op


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
# Warmup Iteration   1: 12.592 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  14.860 ms/op
                 existUser·p0.9999: 25.691 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 3.908 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  25.319 ms/op
                 existUser·p0.9999: 27.338 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.961 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.823 ms/op
                 existUser·p0.999:  15.188 ms/op
                 existUser·p0.9999: 33.153 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242180
  mean =      3.961 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 339 
    [ 2.500,  5.000) = 230596 
    [ 5.000,  7.500) = 8496 
    [ 7.500, 10.000) = 1535 
    [10.000, 12.500) = 677 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     33.958 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 12.725 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.891 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.018 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.025 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  16.063 ms/op
                 getUser·p0.9999: 28.943 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 4.343 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  24.775 ms/op
                 getUser·p0.9999: 27.677 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 31.448 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229550
  mean =      4.181 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 214534 
    [ 5.000,  7.500) = 11441 
    [ 7.500, 10.000) = 2383 
    [10.000, 12.500) = 554 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     29.919 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 14.555 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.002 ±(99.9%) 0.018 ms/op
Iteration   1: 4.888 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.339 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  24.956 ms/op
                 listUser·p0.9999: 29.688 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 4.970 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  20.054 ms/op
                 listUser·p0.9999: 24.005 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.955 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   9.083 ms/op
                 listUser·p0.999:  18.693 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194186
  mean =      4.937 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 146187 
    [ 5.000,  7.500) = 41434 
    [ 7.500, 10.000) = 4853 
    [10.000, 12.500) = 766 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     21.518 ms/op
     p(99.9900) =     27.905 ms/op
     p(99.9990) =     30.033 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.786 ± 8.128  ops/ms
ClientPb.existUser                       thrpt       3   8.201 ± 1.210  ops/ms
ClientPb.getUser                         thrpt       3   7.740 ± 3.118  ops/ms
ClientPb.listUser                        thrpt       3   6.527 ± 0.693  ops/ms
ClientPb.createUser                       avgt       3   4.096 ± 2.439   ms/op
ClientPb.existUser                        avgt       3   3.886 ± 0.457   ms/op
ClientPb.getUser                          avgt       3   4.137 ± 2.083   ms/op
ClientPb.listUser                         avgt       3   4.885 ± 0.659   ms/op
ClientPb.createUser                     sample  232075   4.134 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.665           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.290           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.990           ms/op
ClientPb.createUser:createUser·p0.9999  sample          50.449           ms/op
ClientPb.createUser:createUser·p1.00    sample          60.359           ms/op
ClientPb.existUser                      sample  242180   3.961 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.913           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.671           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  229550   4.181 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.409           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.919           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  194186   4.937 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.309           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.431           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.518           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.905           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
