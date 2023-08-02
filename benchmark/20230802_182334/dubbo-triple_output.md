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
# Warmup Iteration   1: 1.101 ops/ms
# Warmup Iteration   2: 2.543 ops/ms
# Warmup Iteration   3: 5.339 ops/ms
Iteration   1: 5.812 ops/ms
Iteration   2: 6.113 ops/ms
Iteration   3: 6.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.992 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (5.812, 5.992, 6.113), stdev = 0.159
  CI (99.9%): [3.096, 8.888] (assumes normal distribution)


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
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 4.401 ops/ms
# Warmup Iteration   3: 5.678 ops/ms
Iteration   1: 6.022 ops/ms
Iteration   2: 5.979 ops/ms
Iteration   3: 5.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.925 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (5.773, 5.925, 6.022), stdev = 0.133
  CI (99.9%): [3.491, 8.359] (assumes normal distribution)


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
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 4.267 ops/ms
# Warmup Iteration   3: 5.521 ops/ms
Iteration   1: 5.579 ops/ms
Iteration   2: 5.767 ops/ms
Iteration   3: 5.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.708 ±(99.9%) 2.035 ops/ms [Average]
  (min, avg, max) = (5.579, 5.708, 5.777), stdev = 0.112
  CI (99.9%): [3.673, 7.743] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.407 ops/ms
# Warmup Iteration   2: 3.743 ops/ms
# Warmup Iteration   3: 4.870 ops/ms
Iteration   1: 5.002 ops/ms
Iteration   2: 4.987 ops/ms
Iteration   3: 5.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.997 ±(99.9%) 0.156 ops/ms [Average]
  (min, avg, max) = (4.987, 4.997, 5.002), stdev = 0.009
  CI (99.9%): [4.840, 5.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.881 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 7.645 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.634 ±(99.9%) 0.014 ms/op
Iteration   1: 5.860 ±(99.9%) 0.010 ms/op
Iteration   2: 5.667 ±(99.9%) 0.008 ms/op
Iteration   3: 5.350 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.626 ±(99.9%) 4.700 ms/op [Average]
  (min, avg, max) = (5.350, 5.626, 5.860), stdev = 0.258
  CI (99.9%): [0.926, 10.325] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.859 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.604 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.323 ±(99.9%) 0.009 ms/op
Iteration   1: 5.211 ±(99.9%) 0.017 ms/op
Iteration   2: 5.189 ±(99.9%) 0.013 ms/op
Iteration   3: 5.176 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.192 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (5.176, 5.192, 5.211), stdev = 0.018
  CI (99.9%): [4.864, 5.520] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 16.225 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.406 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.008 ms/op
Iteration   1: 5.632 ±(99.9%) 0.012 ms/op
Iteration   2: 5.736 ±(99.9%) 0.006 ms/op
Iteration   3: 5.340 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.569 ±(99.9%) 3.747 ms/op [Average]
  (min, avg, max) = (5.340, 5.569, 5.736), stdev = 0.205
  CI (99.9%): [1.822, 9.316] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.400 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.429 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.543 ±(99.9%) 0.017 ms/op
Iteration   1: 6.377 ±(99.9%) 0.017 ms/op
Iteration   2: 6.475 ±(99.9%) 0.015 ms/op
Iteration   3: 6.171 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.341 ±(99.9%) 2.831 ms/op [Average]
  (min, avg, max) = (6.171, 6.341, 6.475), stdev = 0.155
  CI (99.9%): [3.509, 9.172] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.780 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 6.865 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.028 ms/op
Iteration   1: 5.531 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   10.529 ms/op
                 createUser·p0.999:  23.904 ms/op
                 createUser·p0.9999: 29.840 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   2: 5.620 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.864 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  23.236 ms/op
                 createUser·p0.9999: 26.441 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 5.449 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 28.456 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173414
  mean =      5.532 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 63153 
    [ 5.000,  7.500) = 99486 
    [ 7.500, 10.000) = 8420 
    [10.000, 12.500) = 1685 
    [12.500, 15.000) = 325 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     28.879 ms/op
     p(99.9990) =     30.227 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 16.980 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.097 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.018 ms/op
Iteration   1: 5.358 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  24.784 ms/op
                 existUser·p0.9999: 28.812 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 5.319 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.455 ms/op
                 existUser·p0.95:   7.365 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  26.735 ms/op
                 existUser·p0.9999: 42.794 ms/op
                 existUser·p1.00:   45.023 ms/op

Iteration   3: 5.346 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.003 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  26.457 ms/op
                 existUser·p0.9999: 32.966 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179583
  mean =      5.341 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 84996 
    [ 5.000, 10.000) = 92244 
    [10.000, 15.000) = 1940 
    [15.000, 20.000) = 209 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 118 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     25.638 ms/op
     p(99.9900) =     41.419 ms/op
     p(99.9990) =     45.023 ms/op
     p(99.9999) =     45.023 ms/op
    p(100.0000) =     45.023 ms/op


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
# Warmup Iteration   1: 17.371 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 7.183 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.024 ms/op
Iteration   1: 5.825 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.642 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   9.552 ms/op
                 getUser·p0.99:   13.877 ms/op
                 getUser·p0.999:  28.218 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   36.766 ms/op

Iteration   2: 5.519 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.840 ms/op
                 getUser·p0.99:   10.821 ms/op
                 getUser·p0.999:  25.657 ms/op
                 getUser·p0.9999: 35.927 ms/op
                 getUser·p1.00:   37.093 ms/op

Iteration   3: 5.388 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.449 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.729 ms/op
                 getUser·p0.999:  26.193 ms/op
                 getUser·p0.9999: 32.843 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172319
  mean =      5.572 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 63890 
    [ 5.000,  7.500) = 96407 
    [ 7.500, 10.000) = 7986 
    [10.000, 12.500) = 2508 
    [12.500, 15.000) = 873 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      8.323 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     26.073 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     36.904 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 20.898 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 8.340 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.621 ±(99.9%) 0.029 ms/op
Iteration   1: 6.368 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  28.993 ms/op
                 listUser·p0.9999: 38.074 ms/op
                 listUser·p1.00:   39.125 ms/op

Iteration   2: 6.366 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.498 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  37.078 ms/op
                 listUser·p0.9999: 42.333 ms/op
                 listUser·p1.00:   43.713 ms/op

Iteration   3: 6.731 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.278 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  24.934 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147938
  mean =      6.484 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6620 
    [ 5.000, 10.000) = 136556 
    [10.000, 15.000) = 4111 
    [15.000, 20.000) = 318 
    [20.000, 25.000) = 108 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 82 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.511 ms/op
     p(99.9000) =     29.495 ms/op
     p(99.9900) =     42.088 ms/op
     p(99.9990) =     43.241 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.992 ± 2.896  ops/ms
ClientPb.existUser                       thrpt       3   5.925 ± 2.434  ops/ms
ClientPb.getUser                         thrpt       3   5.708 ± 2.035  ops/ms
ClientPb.listUser                        thrpt       3   4.997 ± 0.156  ops/ms
ClientPb.createUser                       avgt       3   5.626 ± 4.700   ms/op
ClientPb.existUser                        avgt       3   5.192 ± 0.328   ms/op
ClientPb.getUser                          avgt       3   5.569 ± 3.747   ms/op
ClientPb.listUser                         avgt       3   6.341 ± 2.831   ms/op
ClientPb.createUser                     sample  173414   5.532 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.069           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.881           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.469           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.879           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.540           ms/op
ClientPb.existUser                      sample  179583   5.341 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.003           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.668           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.551           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.638           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.419           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.023           ms/op
ClientPb.getUser                        sample  172319   5.572 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.731           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.323           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.124           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.062           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  147938   6.484 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.935           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.511           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.495           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.088           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.713           ms/op
