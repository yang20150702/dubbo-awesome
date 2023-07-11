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
# Warmup Iteration   1: 1.765 ops/ms
# Warmup Iteration   2: 3.542 ops/ms
# Warmup Iteration   3: 7.232 ops/ms
Iteration   1: 7.389 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.907 ±(99.9%) 8.485 ops/ms [Average]
  (min, avg, max) = (7.389, 7.907, 8.289), stdev = 0.465
  CI (99.9%): [≈ 0, 16.393] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 6.853 ops/ms
# Warmup Iteration   3: 8.165 ops/ms
Iteration   1: 8.111 ops/ms
Iteration   2: 8.504 ops/ms
Iteration   3: 8.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.437 ±(99.9%) 5.435 ops/ms [Average]
  (min, avg, max) = (8.111, 8.437, 8.696), stdev = 0.298
  CI (99.9%): [3.002, 13.872] (assumes normal distribution)


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
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 6.422 ops/ms
# Warmup Iteration   3: 7.902 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.542 ops/ms
Iteration   3: 8.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.399 ±(99.9%) 3.889 ops/ms [Average]
  (min, avg, max) = (8.154, 8.399, 8.542), stdev = 0.213
  CI (99.9%): [4.510, 12.288] (assumes normal distribution)


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
# Warmup Iteration   1: 2.217 ops/ms
# Warmup Iteration   2: 5.802 ops/ms
# Warmup Iteration   3: 6.881 ops/ms
Iteration   1: 7.005 ops/ms
Iteration   2: 7.064 ops/ms
Iteration   3: 7.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.048 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (7.005, 7.048, 7.076), stdev = 0.038
  CI (99.9%): [6.357, 7.740] (assumes normal distribution)


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
# Warmup Iteration   1: 13.647 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.005 ms/op
Iteration   1: 3.804 ±(99.9%) 0.013 ms/op
Iteration   2: 3.950 ±(99.9%) 0.008 ms/op
Iteration   3: 3.817 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.857 ±(99.9%) 1.468 ms/op [Average]
  (min, avg, max) = (3.804, 3.857, 3.950), stdev = 0.080
  CI (99.9%): [2.389, 5.325] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.815 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.009 ms/op
Iteration   1: 3.692 ±(99.9%) 0.014 ms/op
Iteration   2: 3.595 ±(99.9%) 0.005 ms/op
Iteration   3: 3.752 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.680 ±(99.9%) 1.439 ms/op [Average]
  (min, avg, max) = (3.595, 3.680, 3.752), stdev = 0.079
  CI (99.9%): [2.241, 5.118] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.836 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.005 ms/op
Iteration   1: 3.981 ±(99.9%) 0.007 ms/op
Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
Iteration   3: 3.885 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.941 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.885, 3.941, 3.981), stdev = 0.050
  CI (99.9%): [3.034, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 13.864 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.499 ±(99.9%) 0.011 ms/op
Iteration   1: 4.433 ±(99.9%) 0.013 ms/op
Iteration   2: 4.459 ±(99.9%) 0.009 ms/op
Iteration   3: 4.692 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.528 ±(99.9%) 2.601 ms/op [Average]
  (min, avg, max) = (4.433, 4.528, 4.692), stdev = 0.143
  CI (99.9%): [1.927, 7.129] (assumes normal distribution)


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
# Warmup Iteration   1: 12.645 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.459 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.293 ±(99.9%) 0.018 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.913 ms/op
                 createUser·p0.999:  21.997 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 27.168 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 3.913 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  25.708 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241256
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 467 
    [ 2.500,  5.000) = 227404 
    [ 5.000,  7.500) = 11111 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     22.405 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.956 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 11.819 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
Iteration   1: 3.846 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  23.319 ms/op
                 existUser·p0.9999: 31.709 ms/op
                 existUser·p1.00:   32.834 ms/op

Iteration   2: 3.822 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.312 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.336 ms/op
                 existUser·p0.999:  16.695 ms/op
                 existUser·p0.9999: 34.396 ms/op
                 existUser·p1.00:   35.127 ms/op

Iteration   3: 3.688 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  27.533 ms/op
                 existUser·p0.9999: 31.009 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253989
  mean =      3.784 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 381 
    [ 2.500,  5.000) = 241217 
    [ 5.000,  7.500) = 10469 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     31.608 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 11.948 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.013 ms/op
Iteration   1: 4.118 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.618 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  15.832 ms/op
                 getUser·p0.9999: 28.811 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   2: 3.880 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 33.718 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.786 ms/op
                 getUser·p0.999:  28.475 ms/op
                 getUser·p0.9999: 31.167 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244247
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 141 
    [ 2.500,  5.000) = 234144 
    [ 5.000,  7.500) = 7507 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 109 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.643 ms/op
     p(99.9900) =     31.902 ms/op
     p(99.9990) =     34.312 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 14.458 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.380 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.020 ms/op
Iteration   1: 4.520 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  22.956 ms/op
                 listUser·p0.9999: 25.849 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 4.468 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   8.195 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 23.326 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 4.578 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.535 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212180
  mean =      4.521 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 192205 
    [ 5.000,  7.500) = 15975 
    [ 7.500, 10.000) = 2974 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.497 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.907 ± 8.485  ops/ms
ClientPb.existUser                       thrpt       3   8.437 ± 5.435  ops/ms
ClientPb.getUser                         thrpt       3   8.399 ± 3.889  ops/ms
ClientPb.listUser                        thrpt       3   7.048 ± 0.691  ops/ms
ClientPb.createUser                       avgt       3   3.857 ± 1.468   ms/op
ClientPb.existUser                        avgt       3   3.680 ± 1.439   ms/op
ClientPb.getUser                          avgt       3   3.941 ± 0.908   ms/op
ClientPb.listUser                         avgt       3   4.528 ± 2.601   ms/op
ClientPb.createUser                     sample  241256   3.980 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.457           ms/op
ClientPb.existUser                      sample  253989   3.784 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.948           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  244247   3.929 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.747           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.643           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.902           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  212180   4.521 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.401           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.727           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
