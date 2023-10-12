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
# Warmup Iteration   1: 1.507 ops/ms
# Warmup Iteration   2: 3.356 ops/ms
# Warmup Iteration   3: 6.997 ops/ms
Iteration   1: 7.310 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 7.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.629 ±(99.9%) 6.220 ops/ms [Average]
  (min, avg, max) = (7.310, 7.629, 7.988), stdev = 0.341
  CI (99.9%): [1.410, 13.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.076 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.286 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (8.199, 8.286, 8.339), stdev = 0.076
  CI (99.9%): [6.901, 9.671] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 6.528 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 7.765 ops/ms
Iteration   3: 7.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.857 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (7.765, 7.857, 7.927), stdev = 0.083
  CI (99.9%): [6.344, 9.369] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.023 ops/ms
# Warmup Iteration   2: 5.763 ops/ms
# Warmup Iteration   3: 6.564 ops/ms
Iteration   1: 6.349 ops/ms
Iteration   2: 6.746 ops/ms
Iteration   3: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.485 ±(99.9%) 4.125 ops/ms [Average]
  (min, avg, max) = (6.349, 6.485, 6.746), stdev = 0.226
  CI (99.9%): [2.360, 10.610] (assumes normal distribution)


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
# Warmup Iteration   1: 13.024 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.005 ms/op
Iteration   1: 4.112 ±(99.9%) 0.005 ms/op
Iteration   2: 4.026 ±(99.9%) 0.005 ms/op
Iteration   3: 4.000 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.046 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (4.000, 4.046, 4.112), stdev = 0.058
  CI (99.9%): [2.982, 5.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.530 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.005 ms/op
Iteration   1: 3.923 ±(99.9%) 0.005 ms/op
Iteration   2: 3.870 ±(99.9%) 0.006 ms/op
Iteration   3: 3.880 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.891 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.870, 3.891, 3.923), stdev = 0.028
  CI (99.9%): [3.382, 4.400] (assumes normal distribution)


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
# Warmup Iteration   1: 11.461 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.003 ms/op
Iteration   1: 4.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.986 ±(99.9%) 0.005 ms/op
Iteration   3: 3.931 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.996 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.931, 3.996, 4.072), stdev = 0.071
  CI (99.9%): [2.700, 5.293] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.972 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.342 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.153 ±(99.9%) 0.007 ms/op
Iteration   1: 4.733 ±(99.9%) 0.008 ms/op
Iteration   2: 4.824 ±(99.9%) 0.009 ms/op
Iteration   3: 4.890 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.816 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (4.733, 4.816, 4.890), stdev = 0.078
  CI (99.9%): [3.384, 6.248] (assumes normal distribution)


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
# Warmup Iteration   1: 12.577 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.018 ms/op
Iteration   1: 4.074 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   8.282 ms/op
                 createUser·p0.999:  23.611 ms/op
                 createUser·p0.9999: 26.580 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.085 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   8.143 ms/op
                 createUser·p0.999:  13.905 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 4.133 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   8.249 ms/op
                 createUser·p0.999:  29.000 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234131
  mean =      4.097 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 457 
    [ 2.500,  5.000) = 216899 
    [ 5.000,  7.500) = 13014 
    [ 7.500, 10.000) = 2761 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     23.851 ms/op
     p(99.9900) =     30.578 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 13.293 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   8.380 ms/op
                 existUser·p0.999:  21.082 ms/op
                 existUser·p0.9999: 26.506 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  16.384 ms/op
                 existUser·p0.9999: 25.698 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.936 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  27.327 ms/op
                 existUser·p0.9999: 34.726 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242633
  mean =      3.956 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 556 
    [ 2.500,  5.000) = 225989 
    [ 5.000,  7.500) = 12175 
    [ 7.500, 10.000) = 2575 
    [10.000, 12.500) = 642 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     34.061 ms/op
     p(99.9990) =     35.006 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 14.338 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.015 ms/op
Iteration   1: 4.040 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.880 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   8.882 ms/op
                 getUser·p0.999:  23.265 ms/op
                 getUser·p0.9999: 29.131 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   2: 4.052 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.964 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  12.599 ms/op
                 getUser·p0.9999: 28.282 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 4.229 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  27.251 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233663
  mean =      4.105 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 217788 
    [ 5.000,  7.500) = 9474 
    [ 7.500, 10.000) = 4949 
    [10.000, 12.500) = 672 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     30.398 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 14.898 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.441 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.032 ±(99.9%) 0.019 ms/op
Iteration   1: 4.802 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   9.818 ms/op
                 listUser·p0.999:  25.573 ms/op
                 listUser·p0.9999: 27.405 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.912 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.577 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 23.085 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.740 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.013 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199291
  mean =      4.817 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 161192 
    [ 5.000,  7.500) = 31577 
    [ 7.500, 10.000) = 4647 
    [10.000, 12.500) = 971 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 311 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     20.405 ms/op
     p(99.9900) =     26.645 ms/op
     p(99.9990) =     27.755 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.629 ± 6.220  ops/ms
ClientPb.existUser                       thrpt       3   8.286 ± 1.385  ops/ms
ClientPb.getUser                         thrpt       3   7.857 ± 1.513  ops/ms
ClientPb.listUser                        thrpt       3   6.485 ± 4.125  ops/ms
ClientPb.createUser                       avgt       3   4.046 ± 1.064   ms/op
ClientPb.existUser                        avgt       3   3.891 ± 0.509   ms/op
ClientPb.getUser                          avgt       3   3.996 ± 1.296   ms/op
ClientPb.listUser                         avgt       3   4.816 ± 1.432   ms/op
ClientPb.createUser                     sample  234131   4.097 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.851           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.578           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  242633   3.956 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.323           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.061           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  233663   4.105 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.077           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.491           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  199291   4.817 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.964           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.405           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.645           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
