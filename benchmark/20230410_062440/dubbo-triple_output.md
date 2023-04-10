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
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 4.632 ops/ms
# Warmup Iteration   3: 7.761 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.227 ±(99.9%) 1.992 ops/ms [Average]
  (min, avg, max) = (8.137, 8.227, 8.348), stdev = 0.109
  CI (99.9%): [6.235, 10.218] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 7.088 ops/ms
# Warmup Iteration   3: 8.522 ops/ms
Iteration   1: 8.575 ops/ms
Iteration   2: 9.036 ops/ms
Iteration   3: 8.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.780 ±(99.9%) 4.280 ops/ms [Average]
  (min, avg, max) = (8.575, 8.780, 9.036), stdev = 0.235
  CI (99.9%): [4.500, 13.061] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.417 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 8.396 ops/ms
Iteration   1: 8.309 ops/ms
Iteration   2: 8.533 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.372 ±(99.9%) 2.567 ops/ms [Average]
  (min, avg, max) = (8.273, 8.372, 8.533), stdev = 0.141
  CI (99.9%): [5.805, 10.939] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 6.003 ops/ms
# Warmup Iteration   3: 7.202 ops/ms
Iteration   1: 7.138 ops/ms
Iteration   2: 7.062 ops/ms
Iteration   3: 7.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.134 ±(99.9%) 1.280 ops/ms [Average]
  (min, avg, max) = (7.062, 7.134, 7.202), stdev = 0.070
  CI (99.9%): [5.855, 8.414] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.000 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.008 ms/op
Iteration   1: 3.872 ±(99.9%) 0.009 ms/op
Iteration   2: 3.770 ±(99.9%) 0.010 ms/op
Iteration   3: 3.732 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.791 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.732, 3.791, 3.872), stdev = 0.073
  CI (99.9%): [2.463, 5.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.899 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.005 ms/op
Iteration   1: 3.629 ±(99.9%) 0.006 ms/op
Iteration   2: 3.688 ±(99.9%) 0.004 ms/op
Iteration   3: 3.507 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.608 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (3.507, 3.608, 3.688), stdev = 0.092
  CI (99.9%): [1.922, 5.294] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.499 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.009 ms/op
Iteration   1: 3.864 ±(99.9%) 0.004 ms/op
Iteration   2: 3.725 ±(99.9%) 0.011 ms/op
Iteration   3: 3.722 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.771 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.722, 3.771, 3.864), stdev = 0.081
  CI (99.9%): [2.293, 5.248] (assumes normal distribution)


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
# Warmup Iteration   1: 14.195 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.045 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.009 ms/op
Iteration   1: 4.471 ±(99.9%) 0.015 ms/op
Iteration   2: 4.485 ±(99.9%) 0.011 ms/op
Iteration   3: 4.493 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.483 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (4.471, 4.483, 4.493), stdev = 0.011
  CI (99.9%): [4.280, 4.686] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.590 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.779 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.018 ms/op
Iteration   1: 3.697 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.942 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  23.593 ms/op
                 createUser·p0.9999: 25.592 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 26.935 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 3.788 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  26.137 ms/op
                 createUser·p0.9999: 34.640 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250183
  mean =      3.837 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1056 
    [ 2.500,  5.000) = 240438 
    [ 5.000,  7.500) = 7541 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     23.980 ms/op
     p(99.9900) =     30.570 ms/op
     p(99.9990) =     37.748 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.332 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.013 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.730 ms/op
                 existUser·p0.9999: 23.897 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.753 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   33.423 ms/op

Iteration   3: 3.645 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  26.542 ms/op
                 existUser·p0.9999: 31.249 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260133
  mean =      3.691 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1576 
    [ 2.500,  5.000) = 248277 
    [ 5.000,  7.500) = 8964 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     12.556 ms/op
     p(99.9900) =     31.653 ms/op
     p(99.9990) =     33.580 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.772 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.011 ms/op
Iteration   1: 3.864 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   5.551 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  22.977 ms/op
                 getUser·p0.9999: 25.269 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 3.800 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.303 ms/op
                 getUser·p0.999:  10.008 ms/op
                 getUser·p0.9999: 26.692 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  28.705 ms/op
                 getUser·p0.9999: 31.130 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250558
  mean =      3.828 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 540 
    [ 2.500,  5.000) = 241703 
    [ 5.000,  7.500) = 6151 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     22.672 ms/op
     p(99.9900) =     30.733 ms/op
     p(99.9990) =     31.489 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.526 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.014 ms/op
Iteration   1: 4.563 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  23.557 ms/op
                 listUser·p0.9999: 27.688 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   2: 4.491 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  18.614 ms/op
                 listUser·p0.9999: 25.293 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 4.681 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.060 ms/op
                 listUser·p0.99:   9.305 ms/op
                 listUser·p0.999:  18.297 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209595
  mean =      4.577 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 182390 
    [ 5.000,  7.500) = 22670 
    [ 7.500, 10.000) = 3409 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     20.854 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     28.828 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.227 ± 1.992  ops/ms
ClientPb.existUser                       thrpt       3   8.780 ± 4.280  ops/ms
ClientPb.getUser                         thrpt       3   8.372 ± 2.567  ops/ms
ClientPb.listUser                        thrpt       3   7.134 ± 1.280  ops/ms
ClientPb.createUser                       avgt       3   3.791 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   3.608 ± 1.686   ms/op
ClientPb.getUser                          avgt       3   3.771 ± 1.477   ms/op
ClientPb.listUser                         avgt       3   4.483 ± 0.203   ms/op
ClientPb.createUser                     sample  250183   3.837 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.513           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.980           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.570           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  260133   3.691 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.556           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.653           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  250558   3.828 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.672           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.733           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  209595   4.577 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.854           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.575           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.934           ms/op
