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
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 3.525 ops/ms
# Warmup Iteration   3: 7.214 ops/ms
Iteration   1: 7.219 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 7.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.526 ±(99.9%) 4.996 ops/ms [Average]
  (min, avg, max) = (7.219, 7.526, 7.745), stdev = 0.274
  CI (99.9%): [2.529, 12.522] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 6.902 ops/ms
# Warmup Iteration   3: 7.881 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.283 ops/ms
Iteration   3: 8.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.193 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (8.123, 8.193, 8.283), stdev = 0.082
  CI (99.9%): [6.699, 9.686] (assumes normal distribution)


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
# Warmup Iteration   1: 2.213 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 7.694 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.882 ±(99.9%) 2.989 ops/ms [Average]
  (min, avg, max) = (7.694, 7.882, 7.993), stdev = 0.164
  CI (99.9%): [4.893, 10.871] (assumes normal distribution)


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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 4.994 ops/ms
# Warmup Iteration   3: 6.467 ops/ms
Iteration   1: 6.542 ops/ms
Iteration   2: 6.817 ops/ms
Iteration   3: 6.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.668 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (6.542, 6.668, 6.817), stdev = 0.139
  CI (99.9%): [4.139, 9.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.676 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.006 ms/op
Iteration   1: 4.217 ±(99.9%) 0.011 ms/op
Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
Iteration   3: 4.051 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.076 ±(99.9%) 2.371 ms/op [Average]
  (min, avg, max) = (3.961, 4.076, 4.217), stdev = 0.130
  CI (99.9%): [1.705, 6.447] (assumes normal distribution)


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
# Warmup Iteration   1: 11.467 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.005 ms/op
Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
Iteration   2: 3.755 ±(99.9%) 0.005 ms/op
Iteration   3: 3.839 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.779 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.742, 3.779, 3.839), stdev = 0.053
  CI (99.9%): [2.821, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 12.558 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 4.141 ±(99.9%) 0.010 ms/op
Iteration   2: 4.087 ±(99.9%) 0.006 ms/op
Iteration   3: 3.953 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.061 ±(99.9%) 1.759 ms/op [Average]
  (min, avg, max) = (3.953, 4.061, 4.141), stdev = 0.096
  CI (99.9%): [2.301, 5.820] (assumes normal distribution)


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
# Warmup Iteration   1: 14.549 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.040 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.770 ±(99.9%) 0.018 ms/op
Iteration   1: 4.683 ±(99.9%) 0.016 ms/op
Iteration   2: 4.720 ±(99.9%) 0.016 ms/op
Iteration   3: 4.700 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.701 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (4.683, 4.701, 4.720), stdev = 0.019
  CI (99.9%): [4.355, 5.046] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.404 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.018 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  23.769 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 4.192 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.688 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 28.447 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 4.182 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  27.525 ms/op
                 createUser·p0.9999: 36.049 ms/op
                 createUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230486
  mean =      4.166 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 211983 
    [ 5.000,  7.500) = 15934 
    [ 7.500, 10.000) = 1580 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 12.303 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
Iteration   1: 3.924 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 30.923 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   2: 4.042 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   8.021 ms/op
                 existUser·p0.999:  25.554 ms/op
                 existUser·p0.9999: 28.839 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.952 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 30.044 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241880
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176 
    [ 2.500,  5.000) = 229473 
    [ 5.000,  7.500) = 10365 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     30.384 ms/op
     p(99.9990) =     31.345 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 14.380 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.014 ms/op
Iteration   1: 4.173 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   8.612 ms/op
                 getUser·p0.999:  23.929 ms/op
                 getUser·p0.9999: 29.010 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 31.490 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   3: 4.280 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  16.253 ms/op
                 getUser·p0.9999: 31.475 ms/op
                 getUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227939
  mean =      4.211 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 206230 
    [ 5.000,  7.500) = 18058 
    [ 7.500, 10.000) = 2605 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     32.839 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 14.762 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.587 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.017 ms/op
Iteration   1: 4.828 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  25.257 ms/op
                 listUser·p0.9999: 27.472 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.712 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   7.626 ms/op
                 listUser·p0.999:  18.422 ms/op
                 listUser·p0.9999: 25.511 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 4.646 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  17.340 ms/op
                 listUser·p0.9999: 22.652 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202855
  mean =      4.727 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 172613 
    [ 5.000,  7.500) = 26703 
    [ 7.500, 10.000) = 2462 
    [10.000, 12.500) = 544 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     20.288 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.890 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.526 ± 4.996  ops/ms
ClientPb.existUser                       thrpt       3   8.193 ± 1.494  ops/ms
ClientPb.getUser                         thrpt       3   7.882 ± 2.989  ops/ms
ClientPb.listUser                        thrpt       3   6.668 ± 2.529  ops/ms
ClientPb.createUser                       avgt       3   4.076 ± 2.371   ms/op
ClientPb.existUser                        avgt       3   3.779 ± 0.958   ms/op
ClientPb.getUser                          avgt       3   4.061 ± 1.759   ms/op
ClientPb.listUser                         avgt       3   4.701 ± 0.346   ms/op
ClientPb.createUser                     sample  230486   4.166 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.865           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  241880   3.964 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.384           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  227939   4.211 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.192           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.350           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.097           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.358           ms/op
ClientPb.listUser                       sample  202855   4.727 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.288           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.327           ms/op
