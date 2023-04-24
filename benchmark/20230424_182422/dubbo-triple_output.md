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
# Warmup Iteration   1: 1.819 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.013 ops/ms
Iteration   2: 8.305 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.854 ±(99.9%) 13.303 ops/ms [Average]
  (min, avg, max) = (7.013, 7.854, 8.305), stdev = 0.729
  CI (99.9%): [≈ 0, 21.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.475 ops/ms
# Warmup Iteration   2: 8.066 ops/ms
# Warmup Iteration   3: 8.592 ops/ms
Iteration   1: 8.823 ops/ms
Iteration   2: 8.797 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.746 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (8.617, 8.746, 8.823), stdev = 0.112
  CI (99.9%): [6.696, 10.795] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 7.609 ops/ms
# Warmup Iteration   3: 8.277 ops/ms
Iteration   1: 8.242 ops/ms
Iteration   2: 8.708 ops/ms
Iteration   3: 8.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.407 ±(99.9%) 4.753 ops/ms [Average]
  (min, avg, max) = (8.242, 8.407, 8.708), stdev = 0.261
  CI (99.9%): [3.654, 13.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.245 ops/ms
# Warmup Iteration   2: 5.788 ops/ms
# Warmup Iteration   3: 6.814 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 6.902 ops/ms
Iteration   3: 7.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.044 ±(99.9%) 2.274 ops/ms [Average]
  (min, avg, max) = (6.902, 7.044, 7.136), stdev = 0.125
  CI (99.9%): [4.770, 9.318] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.739 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.732 ±(99.9%) 0.012 ms/op
Iteration   2: 4.009 ±(99.9%) 0.007 ms/op
Iteration   3: 3.824 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.855 ±(99.9%) 2.576 ms/op [Average]
  (min, avg, max) = (3.732, 3.855, 4.009), stdev = 0.141
  CI (99.9%): [1.279, 6.431] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.662 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.005 ms/op
Iteration   1: 3.715 ±(99.9%) 0.009 ms/op
Iteration   2: 3.773 ±(99.9%) 0.011 ms/op
Iteration   3: 3.639 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.709 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (3.639, 3.709, 3.773), stdev = 0.067
  CI (99.9%): [2.479, 4.939] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.507 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.005 ms/op
Iteration   1: 4.004 ±(99.9%) 0.007 ms/op
Iteration   2: 4.038 ±(99.9%) 0.010 ms/op
Iteration   3: 3.895 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.979 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.895, 3.979, 4.038), stdev = 0.075
  CI (99.9%): [2.617, 5.341] (assumes normal distribution)


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
# Warmup Iteration   1: 13.797 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.454 ±(99.9%) 0.014 ms/op
Iteration   1: 4.451 ±(99.9%) 0.011 ms/op
Iteration   2: 4.439 ±(99.9%) 0.011 ms/op
Iteration   3: 4.573 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.488 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (4.439, 4.488, 4.573), stdev = 0.074
  CI (99.9%): [3.138, 5.837] (assumes normal distribution)


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
# Warmup Iteration   1: 12.589 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.779 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.020 ms/op
Iteration   1: 3.801 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 36.815 ms/op
                 createUser·p1.00:   39.649 ms/op

Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.478 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 25.087 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.818 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  26.219 ms/op
                 createUser·p0.9999: 31.445 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250042
  mean =      3.838 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 512 
    [ 2.500,  5.000) = 240073 
    [ 5.000,  7.500) = 7271 
    [ 7.500, 10.000) = 1627 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     21.593 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     39.551 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 11.110 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.011 ms/op
Iteration   1: 3.683 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  10.473 ms/op
                 existUser·p0.9999: 24.609 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.657 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.881 ms/op
                 existUser·p0.999:  24.096 ms/op
                 existUser·p0.9999: 27.036 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.713 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  12.532 ms/op
                 existUser·p0.9999: 33.646 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260218
  mean =      3.684 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1475 
    [ 2.500,  5.000) = 252010 
    [ 5.000,  7.500) = 5288 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     12.638 ms/op
     p(99.9900) =     31.746 ms/op
     p(99.9990) =     34.170 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 12.394 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.013 ms/op
Iteration   1: 3.667 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 30.188 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   2: 3.748 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.890 ms/op
                 getUser·p0.999:  23.135 ms/op
                 getUser·p0.9999: 26.547 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.779 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  25.110 ms/op
                 getUser·p0.9999: 30.759 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 257329
  mean =      3.730 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3198 
    [ 2.500,  5.000) = 242446 
    [ 5.000,  7.500) = 9565 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     31.967 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 14.135 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.657 ±(99.9%) 0.017 ms/op
Iteration   1: 4.742 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   9.209 ms/op
                 listUser·p0.999:  29.983 ms/op
                 listUser·p0.9999: 34.472 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   2: 4.437 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.015 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.354 ms/op
                 listUser·p0.999:  18.346 ms/op
                 listUser·p0.9999: 21.946 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.412 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212109
  mean =      4.525 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 185138 
    [ 5.000,  7.500) = 22544 
    [ 7.500, 10.000) = 3123 
    [10.000, 12.500) = 621 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     18.412 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     35.250 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.854 ± 13.303  ops/ms
ClientPb.existUser                       thrpt       3   8.746 ±  2.049  ops/ms
ClientPb.getUser                         thrpt       3   8.407 ±  4.753  ops/ms
ClientPb.listUser                        thrpt       3   7.044 ±  2.274  ops/ms
ClientPb.createUser                       avgt       3   3.855 ±  2.576   ms/op
ClientPb.existUser                        avgt       3   3.709 ±  1.230   ms/op
ClientPb.getUser                          avgt       3   3.979 ±  1.362   ms/op
ClientPb.listUser                         avgt       3   4.488 ±  1.350   ms/op
ClientPb.createUser                     sample  250042   3.838 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.724            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.682            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.358            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.193            ms/op
ClientPb.createUser:createUser·p0.999   sample          21.593            ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.193            ms/op
ClientPb.createUser:createUser·p1.00    sample          39.649            ms/op
ClientPb.existUser                      sample  260218   3.684 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.588            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.084            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.424            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.423            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.638            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.746            ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210            ms/op
ClientPb.getUser                        sample  257329   3.730 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.749            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.592            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.334            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.333            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.147            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276            ms/op
ClientPb.listUser                       sample  212109   4.525 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.342            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.767            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.634            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.412            ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.260            ms/op
ClientPb.listUser:listUser·p1.00        sample          35.521            ms/op
