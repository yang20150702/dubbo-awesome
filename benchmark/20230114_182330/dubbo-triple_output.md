# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.137 ops/ms
# Warmup Iteration   2: 3.178 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.192 ops/ms
Iteration   2: 6.143 ops/ms
Iteration   3: 6.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.198 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (6.143, 6.198, 6.258), stdev = 0.058
  CI (99.9%): [5.148, 7.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.786 ops/ms
# Warmup Iteration   2: 5.678 ops/ms
# Warmup Iteration   3: 6.341 ops/ms
Iteration   1: 6.665 ops/ms
Iteration   2: 6.532 ops/ms
Iteration   3: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.619 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (6.532, 6.619, 6.665), stdev = 0.076
  CI (99.9%): [5.234, 8.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 4.725 ops/ms
# Warmup Iteration   3: 6.182 ops/ms
Iteration   1: 5.883 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.123 ±(99.9%) 4.583 ops/ms [Average]
  (min, avg, max) = (5.883, 6.123, 6.384), stdev = 0.251
  CI (99.9%): [1.540, 10.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.752 ops/ms
# Warmup Iteration   2: 4.736 ops/ms
# Warmup Iteration   3: 5.356 ops/ms
Iteration   1: 5.278 ops/ms
Iteration   2: 5.531 ops/ms
Iteration   3: 5.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.408 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (5.278, 5.408, 5.531), stdev = 0.127
  CI (99.9%): [3.095, 7.720] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.515 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.236 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.191 ±(99.9%) 0.013 ms/op
Iteration   1: 4.858 ±(99.9%) 0.014 ms/op
Iteration   2: 5.001 ±(99.9%) 0.014 ms/op
Iteration   3: 5.101 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.987 ±(99.9%) 2.225 ms/op [Average]
  (min, avg, max) = (4.858, 4.987, 5.101), stdev = 0.122
  CI (99.9%): [2.762, 7.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.811 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.120 ±(99.9%) 0.010 ms/op
Iteration   1: 4.984 ±(99.9%) 0.015 ms/op
Iteration   2: 4.964 ±(99.9%) 0.012 ms/op
Iteration   3: 4.920 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.956 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (4.920, 4.956, 4.984), stdev = 0.033
  CI (99.9%): [4.357, 5.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.356 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.241 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.516 ±(99.9%) 0.014 ms/op
Iteration   1: 5.507 ±(99.9%) 0.017 ms/op
Iteration   2: 5.268 ±(99.9%) 0.009 ms/op
Iteration   3: 5.391 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.389 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (5.268, 5.389, 5.507), stdev = 0.119
  CI (99.9%): [3.214, 7.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.844 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.937 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.928 ±(99.9%) 0.021 ms/op
Iteration   1: 6.038 ±(99.9%) 0.017 ms/op
Iteration   2: 5.898 ±(99.9%) 0.017 ms/op
Iteration   3: 5.680 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.872 ±(99.9%) 3.293 ms/op [Average]
  (min, avg, max) = (5.680, 5.872, 6.038), stdev = 0.181
  CI (99.9%): [2.579, 9.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.992 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 6.502 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.597 ±(99.9%) 0.024 ms/op
Iteration   1: 5.344 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.833 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  23.047 ms/op
                 createUser·p0.9999: 30.638 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   2: 5.107 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  24.196 ms/op
                 createUser·p0.9999: 28.139 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 5.349 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.520 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  24.880 ms/op
                 createUser·p0.9999: 29.200 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182136
  mean =      5.264 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 95499 
    [ 5.000,  7.500) = 78322 
    [ 7.500, 10.000) = 6473 
    [10.000, 12.500) = 1126 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     23.195 ms/op
     p(99.9900) =     29.222 ms/op
     p(99.9990) =     31.426 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.521 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 5.815 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.127 ±(99.9%) 0.018 ms/op
Iteration   1: 4.942 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  21.270 ms/op
                 existUser·p0.9999: 25.675 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   2: 5.151 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.594 ms/op
                 existUser·p0.99:   10.748 ms/op
                 existUser·p0.999:  17.236 ms/op
                 existUser·p0.9999: 28.095 ms/op
                 existUser·p1.00:   32.211 ms/op

Iteration   3: 4.951 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   5.890 ms/op
                 existUser·p0.95:   6.636 ms/op
                 existUser·p0.99:   9.175 ms/op
                 existUser·p0.999:  22.889 ms/op
                 existUser·p0.9999: 29.908 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191337
  mean =      5.013 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 126804 
    [ 5.000,  7.500) = 57222 
    [ 7.500, 10.000) = 5398 
    [10.000, 12.500) = 1186 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     31.612 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.962 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.178 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.265 ±(99.9%) 0.019 ms/op
Iteration   1: 5.193 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   11.256 ms/op
                 getUser·p0.999:  22.525 ms/op
                 getUser·p0.9999: 28.498 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 5.230 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   7.246 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  23.760 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 5.151 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   7.274 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  24.671 ms/op
                 getUser·p0.9999: 29.222 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184838
  mean =      5.191 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 106050 
    [ 5.000,  7.500) = 69849 
    [ 7.500, 10.000) = 6715 
    [10.000, 12.500) = 1153 
    [12.500, 15.000) = 548 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.952 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     23.238 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     29.984 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.829 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.298 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.587 ±(99.9%) 0.035 ms/op
Iteration   1: 6.413 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  27.689 ms/op
                 listUser·p0.9999: 51.318 ms/op
                 listUser·p1.00:   52.101 ms/op

Iteration   2: 6.199 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  27.191 ms/op
                 listUser·p0.9999: 35.652 ms/op
                 listUser·p1.00:   36.569 ms/op

Iteration   3: 6.008 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  23.387 ms/op
                 listUser·p0.9999: 31.305 ms/op
                 listUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154650
  mean =      6.202 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16045 
    [ 5.000, 10.000) = 133411 
    [10.000, 15.000) = 4502 
    [15.000, 20.000) = 342 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 24 
    [50.000, 55.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.894 ms/op
     p(99.9000) =     26.870 ms/op
     p(99.9900) =     49.157 ms/op
     p(99.9990) =     51.850 ms/op
     p(99.9999) =     52.101 ms/op
    p(100.0000) =     52.101 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.198 ± 1.050  ops/ms
ClientPb.existUser                       thrpt       3   6.619 ± 1.386  ops/ms
ClientPb.getUser                         thrpt       3   6.123 ± 4.583  ops/ms
ClientPb.listUser                        thrpt       3   5.408 ± 2.312  ops/ms
ClientPb.createUser                       avgt       3   4.987 ± 2.225   ms/op
ClientPb.existUser                        avgt       3   4.956 ± 0.599   ms/op
ClientPb.getUser                          avgt       3   5.389 ± 2.175   ms/op
ClientPb.listUser                         avgt       3   5.872 ± 3.293   ms/op
ClientPb.createUser                     sample  182136   5.264 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.195           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  191337   5.013 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.896           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  184838   5.191 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.952           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.447           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.238           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.574           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.457           ms/op
ClientPb.listUser                       sample  154650   6.202 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.894           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.870           ms/op
ClientPb.listUser:listUser·p0.9999      sample          49.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          52.101           ms/op
