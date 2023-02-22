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
# Warmup Iteration   1: 1.244 ops/ms
# Warmup Iteration   2: 2.878 ops/ms
# Warmup Iteration   3: 6.091 ops/ms
Iteration   1: 6.189 ops/ms
Iteration   2: 6.487 ops/ms
Iteration   3: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.411 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (6.189, 6.411, 6.556), stdev = 0.195
  CI (99.9%): [2.855, 9.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.855 ops/ms
# Warmup Iteration   2: 6.052 ops/ms
# Warmup Iteration   3: 6.849 ops/ms
Iteration   1: 7.278 ops/ms
Iteration   2: 6.989 ops/ms
Iteration   3: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.036 ±(99.9%) 4.049 ops/ms [Average]
  (min, avg, max) = (6.842, 7.036, 7.278), stdev = 0.222
  CI (99.9%): [2.987, 11.085] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.632 ops/ms
# Warmup Iteration   2: 5.657 ops/ms
# Warmup Iteration   3: 6.402 ops/ms
Iteration   1: 6.475 ops/ms
Iteration   2: 6.627 ops/ms
Iteration   3: 6.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.619 ±(99.9%) 2.547 ops/ms [Average]
  (min, avg, max) = (6.475, 6.619, 6.754), stdev = 0.140
  CI (99.9%): [4.072, 9.166] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 4.693 ops/ms
# Warmup Iteration   3: 5.502 ops/ms
Iteration   1: 5.715 ops/ms
Iteration   2: 5.727 ops/ms
Iteration   3: 5.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.757 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (5.715, 5.757, 5.830), stdev = 0.063
  CI (99.9%): [4.602, 6.912] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.398 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.575 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.013 ms/op
Iteration   1: 4.749 ±(99.9%) 0.014 ms/op
Iteration   2: 4.814 ±(99.9%) 0.012 ms/op
Iteration   3: 4.605 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.723 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (4.605, 4.723, 4.814), stdev = 0.107
  CI (99.9%): [2.773, 6.672] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 13.893 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.670 ±(99.9%) 0.013 ms/op
Iteration   1: 4.665 ±(99.9%) 0.004 ms/op
Iteration   2: 4.541 ±(99.9%) 0.010 ms/op
Iteration   3: 4.579 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.595 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (4.541, 4.595, 4.665), stdev = 0.063
  CI (99.9%): [3.439, 5.752] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 16.406 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.865 ±(99.9%) 0.008 ms/op
Iteration   1: 4.731 ±(99.9%) 0.014 ms/op
Iteration   2: 4.887 ±(99.9%) 0.013 ms/op
Iteration   3: 4.887 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.835 ±(99.9%) 1.639 ms/op [Average]
  (min, avg, max) = (4.731, 4.835, 4.887), stdev = 0.090
  CI (99.9%): [3.196, 6.474] (assumes normal distribution)


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
# Warmup Iteration   1: 17.022 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 7.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.730 ±(99.9%) 0.016 ms/op
Iteration   1: 5.531 ±(99.9%) 0.014 ms/op
Iteration   2: 5.455 ±(99.9%) 0.017 ms/op
Iteration   3: 5.488 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.492 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (5.455, 5.492, 5.531), stdev = 0.038
  CI (99.9%): [4.796, 6.187] (assumes normal distribution)


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
# Warmup Iteration   1: 16.764 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.058 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.357 ±(99.9%) 0.023 ms/op
Iteration   1: 4.935 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  16.704 ms/op
                 createUser·p0.9999: 25.314 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 4.860 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.636 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  19.643 ms/op
                 createUser·p0.9999: 30.095 ms/op
                 createUser·p1.00:   31.326 ms/op

Iteration   3: 4.794 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.275 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  27.689 ms/op
                 createUser·p0.9999: 29.819 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 197232
  mean =      4.862 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 141639 
    [ 5.000,  7.500) = 50760 
    [ 7.500, 10.000) = 3485 
    [10.000, 12.500) = 822 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      9.022 ms/op
     p(99.9000) =     23.111 ms/op
     p(99.9900) =     29.640 ms/op
     p(99.9990) =     32.836 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 13.920 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.016 ms/op
Iteration   1: 4.433 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  19.630 ms/op
                 existUser·p0.9999: 27.471 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 4.453 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.015 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 27.349 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 4.644 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.815 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 28.312 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 212810
  mean =      4.508 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 177575 
    [ 5.000,  7.500) = 30904 
    [ 7.500, 10.000) = 3001 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 15.971 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.686 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.949 ±(99.9%) 0.017 ms/op
Iteration   1: 4.958 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.306 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  24.001 ms/op
                 getUser·p0.9999: 27.412 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 4.717 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  17.662 ms/op
                 getUser·p0.9999: 27.671 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   3: 4.932 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  19.481 ms/op
                 getUser·p0.9999: 28.116 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 197144
  mean =      4.866 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 144253 
    [ 5.000,  7.500) = 45950 
    [ 7.500, 10.000) = 4947 
    [10.000, 12.500) = 1147 
    [12.500, 15.000) = 477 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =     10.003 ms/op
     p(99.9000) =     23.771 ms/op
     p(99.9900) =     27.731 ms/op
     p(99.9990) =     28.587 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 17.331 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 6.452 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.023 ms/op
Iteration   1: 5.658 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  26.503 ms/op
                 listUser·p0.9999: 29.602 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   2: 5.117 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.745 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  24.084 ms/op
                 listUser·p0.9999: 27.935 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   3: 5.690 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  20.571 ms/op
                 listUser·p0.9999: 24.011 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 175328
  mean =      5.475 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 67741 
    [ 5.000,  7.500) = 97960 
    [ 7.500, 10.000) = 7262 
    [10.000, 12.500) = 1560 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     23.593 ms/op
     p(99.9900) =     28.949 ms/op
     p(99.9990) =     30.588 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.411 ± 3.556  ops/ms
ClientPb.existUser                       thrpt       3   7.036 ± 4.049  ops/ms
ClientPb.getUser                         thrpt       3   6.619 ± 2.547  ops/ms
ClientPb.listUser                        thrpt       3   5.757 ± 1.155  ops/ms
ClientPb.createUser                       avgt       3   4.723 ± 1.949   ms/op
ClientPb.existUser                        avgt       3   4.595 ± 1.157   ms/op
ClientPb.getUser                          avgt       3   4.835 ± 1.639   ms/op
ClientPb.listUser                         avgt       3   5.492 ± 0.695   ms/op
ClientPb.createUser                     sample  197232   4.862 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.022           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.111           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.640           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  212810   4.508 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.153           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  197144   4.866 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.003           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.771           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.731           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  175328   5.475 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.718           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.600           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.593           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.949           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.736           ms/op
