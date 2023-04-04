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
# Warmup Iteration   1: 1.211 ops/ms
# Warmup Iteration   2: 2.665 ops/ms
# Warmup Iteration   3: 5.650 ops/ms
Iteration   1: 5.383 ops/ms
Iteration   2: 5.799 ops/ms
Iteration   3: 5.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.664 ±(99.9%) 4.435 ops/ms [Average]
  (min, avg, max) = (5.383, 5.664, 5.810), stdev = 0.243
  CI (99.9%): [1.229, 10.099] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 5.566 ops/ms
# Warmup Iteration   3: 6.282 ops/ms
Iteration   1: 6.174 ops/ms
Iteration   2: 6.114 ops/ms
Iteration   3: 6.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.152 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (6.114, 6.152, 6.174), stdev = 0.033
  CI (99.9%): [5.549, 6.754] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 5.217 ops/ms
# Warmup Iteration   3: 5.946 ops/ms
Iteration   1: 5.851 ops/ms
Iteration   2: 6.005 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.064 ±(99.9%) 4.527 ops/ms [Average]
  (min, avg, max) = (5.851, 6.064, 6.336), stdev = 0.248
  CI (99.9%): [1.537, 10.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 4.022 ops/ms
# Warmup Iteration   3: 4.855 ops/ms
Iteration   1: 4.960 ops/ms
Iteration   2: 4.766 ops/ms
Iteration   3: 4.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.850 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (4.766, 4.850, 4.960), stdev = 0.100
  CI (99.9%): [3.029, 6.670] (assumes normal distribution)


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
# Warmup Iteration   1: 17.592 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.416 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.010 ms/op
Iteration   1: 5.056 ±(99.9%) 0.013 ms/op
Iteration   2: 4.985 ±(99.9%) 0.013 ms/op
Iteration   3: 5.122 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.054 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (4.985, 5.054, 5.122), stdev = 0.068
  CI (99.9%): [3.807, 6.301] (assumes normal distribution)


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
# Warmup Iteration   1: 14.450 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.007 ms/op
Iteration   1: 4.956 ±(99.9%) 0.011 ms/op
Iteration   2: 4.820 ±(99.9%) 0.011 ms/op
Iteration   3: 5.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.929 ±(99.9%) 1.793 ms/op [Average]
  (min, avg, max) = (4.820, 4.929, 5.011), stdev = 0.098
  CI (99.9%): [3.136, 6.722] (assumes normal distribution)


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
# Warmup Iteration   1: 15.422 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.964 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.009 ms/op
Iteration   1: 5.486 ±(99.9%) 0.011 ms/op
Iteration   2: 5.255 ±(99.9%) 0.014 ms/op
Iteration   3: 5.657 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.466 ±(99.9%) 3.681 ms/op [Average]
  (min, avg, max) = (5.255, 5.466, 5.657), stdev = 0.202
  CI (99.9%): [1.785, 9.147] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 19.006 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 7.742 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.855 ±(99.9%) 0.015 ms/op
Iteration   1: 6.402 ±(99.9%) 0.017 ms/op
Iteration   2: 6.521 ±(99.9%) 0.023 ms/op
Iteration   3: 6.425 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.450 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (6.402, 6.450, 6.521), stdev = 0.063
  CI (99.9%): [5.296, 7.603] (assumes normal distribution)


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
# Warmup Iteration   1: 16.816 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.279 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.383 ±(99.9%) 0.023 ms/op
Iteration   1: 5.137 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.168 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  22.082 ms/op
                 createUser·p0.9999: 27.734 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   2: 5.272 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   4.944 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.174 ms/op
                 createUser·p0.999:  29.131 ms/op
                 createUser·p0.9999: 36.897 ms/op
                 createUser·p1.00:   38.339 ms/op

Iteration   3: 5.244 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  26.836 ms/op
                 createUser·p0.9999: 31.971 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 183970
  mean =      5.217 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 100463 
    [ 5.000,  7.500) = 74030 
    [ 7.500, 10.000) = 7774 
    [10.000, 12.500) = 1153 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     22.840 ms/op
     p(99.9900) =     35.626 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 15.556 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.370 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.540 ±(99.9%) 0.021 ms/op
Iteration   1: 5.200 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.390 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  23.111 ms/op
                 existUser·p0.9999: 26.583 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 5.408 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   8.020 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  15.532 ms/op
                 existUser·p0.9999: 30.384 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   3: 5.065 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  31.233 ms/op
                 existUser·p0.9999: 33.249 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183855
  mean =      5.221 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 99143 
    [ 5.000,  7.500) = 76205 
    [ 7.500, 10.000) = 6520 
    [10.000, 12.500) = 1269 
    [12.500, 15.000) = 402 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     33.018 ms/op
     p(99.9990) =     33.715 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 17.393 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.901 ±(99.9%) 0.026 ms/op
Iteration   1: 5.591 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.348 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  22.683 ms/op
                 getUser·p0.9999: 27.579 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 5.364 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.709 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 27.597 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 5.174 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.187 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  27.254 ms/op
                 getUser·p0.9999: 32.291 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178694
  mean =      5.371 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 88322 
    [ 5.000,  7.500) = 78689 
    [ 7.500, 10.000) = 9233 
    [10.000, 12.500) = 1668 
    [12.500, 15.000) = 463 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     32.613 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 17.840 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.042 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.021 ms/op
Iteration   1: 6.237 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  28.060 ms/op
                 listUser·p0.9999: 39.224 ms/op
                 listUser·p1.00:   40.108 ms/op

Iteration   2: 5.957 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  25.208 ms/op
                 listUser·p0.9999: 29.181 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   3: 5.881 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  23.493 ms/op
                 listUser·p0.9999: 26.957 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159274
  mean =      6.021 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 25815 
    [ 5.000, 10.000) = 129515 
    [10.000, 15.000) = 3376 
    [15.000, 20.000) = 220 
    [20.000, 25.000) = 160 
    [25.000, 30.000) = 150 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.005 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     36.902 ms/op
     p(99.9990) =     39.953 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.664 ± 4.435  ops/ms
ClientPb.existUser                       thrpt       3   6.152 ± 0.603  ops/ms
ClientPb.getUser                         thrpt       3   6.064 ± 4.527  ops/ms
ClientPb.listUser                        thrpt       3   4.850 ± 1.821  ops/ms
ClientPb.createUser                       avgt       3   5.054 ± 1.247   ms/op
ClientPb.existUser                        avgt       3   4.929 ± 1.793   ms/op
ClientPb.getUser                          avgt       3   5.466 ± 3.681   ms/op
ClientPb.listUser                         avgt       3   6.450 ± 1.154   ms/op
ClientPb.createUser                     sample  183970   5.217 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.473           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.528           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.847           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.840           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.626           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.339           ms/op
ClientPb.existUser                      sample  183855   5.221 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.009           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.513           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.174           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.466           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  178694   5.371 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.840           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.486           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.654           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  159274   6.021 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.005           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.878           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.297           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.902           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.108           ms/op
