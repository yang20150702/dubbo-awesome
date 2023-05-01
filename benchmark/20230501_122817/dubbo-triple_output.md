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
# Warmup Iteration   1: 1.665 ops/ms
# Warmup Iteration   2: 3.700 ops/ms
# Warmup Iteration   3: 7.507 ops/ms
Iteration   1: 7.360 ops/ms
Iteration   2: 7.636 ops/ms
Iteration   3: 8.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.690 ±(99.9%) 6.567 ops/ms [Average]
  (min, avg, max) = (7.360, 7.690, 8.074), stdev = 0.360
  CI (99.9%): [1.123, 14.257] (assumes normal distribution)


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
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.667 ops/ms
# Warmup Iteration   3: 7.946 ops/ms
Iteration   1: 8.607 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.508 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (8.275, 8.508, 8.642), stdev = 0.203
  CI (99.9%): [4.813, 12.203] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.381 ops/ms
# Warmup Iteration   2: 6.630 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.145 ±(99.9%) 4.901 ops/ms [Average]
  (min, avg, max) = (7.972, 8.145, 8.455), stdev = 0.269
  CI (99.9%): [3.244, 13.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.100 ops/ms
# Warmup Iteration   3: 6.628 ops/ms
Iteration   1: 7.047 ops/ms
Iteration   2: 7.292 ops/ms
Iteration   3: 7.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.142 ±(99.9%) 2.393 ops/ms [Average]
  (min, avg, max) = (7.047, 7.142, 7.292), stdev = 0.131
  CI (99.9%): [4.748, 9.535] (assumes normal distribution)


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
# Warmup Iteration   1: 13.166 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.637 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.006 ms/op
Iteration   1: 4.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.816 ±(99.9%) 0.013 ms/op
Iteration   3: 3.781 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.891 ±(99.9%) 2.926 ms/op [Average]
  (min, avg, max) = (3.781, 3.891, 4.075), stdev = 0.160
  CI (99.9%): [0.965, 6.817] (assumes normal distribution)


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
# Warmup Iteration   1: 11.798 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.007 ms/op
Iteration   1: 3.938 ±(99.9%) 0.005 ms/op
Iteration   2: 3.729 ±(99.9%) 0.006 ms/op
Iteration   3: 3.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.866 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (3.729, 3.866, 3.938), stdev = 0.119
  CI (99.9%): [1.695, 6.037] (assumes normal distribution)


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
# Warmup Iteration   1: 12.081 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.005 ms/op
Iteration   1: 3.997 ±(99.9%) 0.010 ms/op
Iteration   2: 3.863 ±(99.9%) 0.010 ms/op
Iteration   3: 4.056 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.972 ±(99.9%) 1.812 ms/op [Average]
  (min, avg, max) = (3.863, 3.972, 4.056), stdev = 0.099
  CI (99.9%): [2.160, 5.784] (assumes normal distribution)


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
# Warmup Iteration   1: 14.256 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.009 ms/op
Iteration   1: 4.531 ±(99.9%) 0.015 ms/op
Iteration   2: 4.475 ±(99.9%) 0.012 ms/op
Iteration   3: 4.320 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.442 ±(99.9%) 1.990 ms/op [Average]
  (min, avg, max) = (4.320, 4.442, 4.531), stdev = 0.109
  CI (99.9%): [2.452, 6.432] (assumes normal distribution)


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
# Warmup Iteration   1: 11.885 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.776 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.018 ms/op
Iteration   1: 3.922 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  23.167 ms/op
                 createUser·p0.9999: 28.274 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 3.846 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  24.722 ms/op
                 createUser·p0.9999: 28.164 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 29.524 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245714
  mean =      3.904 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1339 
    [ 2.500,  5.000) = 229542 
    [ 5.000,  7.500) = 12549 
    [ 7.500, 10.000) = 1513 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     23.045 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.221 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 11.383 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.723 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.535 ms/op
                 existUser·p0.999:  23.301 ms/op
                 existUser·p0.9999: 27.377 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   2: 3.718 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 25.781 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   3: 3.715 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.903 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  26.804 ms/op
                 existUser·p0.9999: 33.437 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258081
  mean =      3.719 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2906 
    [ 2.500,  5.000) = 242537 
    [ 5.000,  7.500) = 11000 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     16.465 ms/op
     p(99.9900) =     31.955 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 12.552 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.019 ms/op
Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.421 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.840 ms/op
                 getUser·p0.999:  10.797 ms/op
                 getUser·p0.9999: 27.046 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.880 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  24.626 ms/op
                 getUser·p0.9999: 27.263 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.825 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  8.920 ms/op
                 getUser·p0.9999: 34.079 ms/op
                 getUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247027
  mean =      3.886 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 496 
    [ 2.500,  5.000) = 234040 
    [ 5.000,  7.500) = 9791 
    [ 7.500, 10.000) = 2215 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     14.073 ms/op
     p(99.9900) =     32.291 ms/op
     p(99.9990) =     34.144 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.040 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.286 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.043 ±(99.9%) 0.021 ms/op
Iteration   1: 4.601 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  25.083 ms/op
                 listUser·p0.9999: 31.986 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 4.592 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.674 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 20.648 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.611 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208445
  mean =      4.601 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 178770 
    [ 5.000,  7.500) = 25727 
    [ 7.500, 10.000) = 2741 
    [10.000, 12.500) = 578 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     19.613 ms/op
     p(99.9900) =     29.943 ms/op
     p(99.9990) =     32.719 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.690 ± 6.567  ops/ms
ClientPb.existUser                       thrpt       3   8.508 ± 3.695  ops/ms
ClientPb.getUser                         thrpt       3   8.145 ± 4.901  ops/ms
ClientPb.listUser                        thrpt       3   7.142 ± 2.393  ops/ms
ClientPb.createUser                       avgt       3   3.891 ± 2.926   ms/op
ClientPb.existUser                        avgt       3   3.866 ± 2.171   ms/op
ClientPb.getUser                          avgt       3   3.972 ± 1.812   ms/op
ClientPb.listUser                         avgt       3   4.442 ± 1.990   ms/op
ClientPb.createUser                     sample  245714   3.904 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.628           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.045           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  258081   3.719 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.013           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  247027   3.886 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.291           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  208445   4.601 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.613           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.943           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.735           ms/op
