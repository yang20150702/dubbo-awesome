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
# Warmup Iteration   1: 2.580 ops/ms
# Warmup Iteration   2: 6.153 ops/ms
# Warmup Iteration   3: 9.191 ops/ms
Iteration   1: 9.635 ops/ms
Iteration   2: 9.863 ops/ms
Iteration   3: 9.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.794 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (9.635, 9.794, 9.883), stdev = 0.138
  CI (99.9%): [7.281, 12.307] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.549 ops/ms
# Warmup Iteration   2: 9.430 ops/ms
# Warmup Iteration   3: 10.177 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.157 ±(99.9%) 7.150 ops/ms [Average]
  (min, avg, max) = (9.923, 10.157, 10.609), stdev = 0.392
  CI (99.9%): [3.007, 17.307] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 9.073 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.570 ±(99.9%) 8.888 ops/ms [Average]
  (min, avg, max) = (9.026, 9.570, 9.965), stdev = 0.487
  CI (99.9%): [0.682, 18.458] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 7.029 ops/ms
# Warmup Iteration   3: 8.222 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.260 ±(99.9%) 2.879 ops/ms [Average]
  (min, avg, max) = (8.141, 8.260, 8.439), stdev = 0.158
  CI (99.9%): [5.382, 11.139] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.510 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.005 ms/op
Iteration   1: 3.270 ±(99.9%) 0.002 ms/op
Iteration   2: 3.389 ±(99.9%) 0.006 ms/op
Iteration   3: 3.289 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (3.270, 3.316, 3.389), stdev = 0.064
  CI (99.9%): [2.155, 4.477] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.713 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.004 ms/op
Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
Iteration   3: 3.150 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.159 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (3.143, 3.159, 3.184), stdev = 0.022
  CI (99.9%): [2.762, 3.556] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.497 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.155 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
Iteration   3: 3.143 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.152 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.143, 3.152, 3.158), stdev = 0.008
  CI (99.9%): [3.010, 3.295] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.786 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.004 ms/op
Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
Iteration   2: 3.778 ±(99.9%) 0.006 ms/op
Iteration   3: 3.790 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.702, 3.757, 3.790), stdev = 0.048
  CI (99.9%): [2.887, 4.626] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.729 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.010 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.463 ms/op
                 createUser·p0.9999: 21.807 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.190 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  15.348 ms/op
                 createUser·p0.9999: 20.540 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293856
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19894 
    [ 2.500,  5.000) = 266945 
    [ 5.000,  7.500) = 5869 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     23.732 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.629 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 25.136 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.167 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  16.952 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   35.521 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308249
  mean =      3.113 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15059 
    [ 2.500,  5.000) = 288701 
    [ 5.000,  7.500) = 3593 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     14.897 ms/op
     p(99.9900) =     33.373 ms/op
     p(99.9990) =     35.242 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
Iteration   1: 3.250 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  15.659 ms/op
                 getUser·p0.9999: 25.368 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.259 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  11.694 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 25.162 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294747
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15035 
    [ 2.500,  5.000) = 270814 
    [ 5.000,  7.500) = 7766 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     15.520 ms/op
     p(99.9900) =     25.806 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.680 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.822 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.892 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 21.975 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.801 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.148 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252453
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 244498 
    [ 5.000,  7.500) = 5969 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     22.823 ms/op
     p(99.9990) =     24.100 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.794 ± 2.513  ops/ms
ClientPb.existUser                       thrpt       3  10.157 ± 7.150  ops/ms
ClientPb.getUser                         thrpt       3   9.570 ± 8.888  ops/ms
ClientPb.listUser                        thrpt       3   8.260 ± 2.879  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 1.161   ms/op
ClientPb.existUser                        avgt       3   3.159 ± 0.397   ms/op
ClientPb.getUser                          avgt       3   3.152 ± 0.142   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 0.869   ms/op
ClientPb.createUser                     sample  293856   3.264 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.732           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  308249   3.113 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.722           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.897           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.373           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  294747   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.806           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  252453   3.805 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.266           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.823           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
