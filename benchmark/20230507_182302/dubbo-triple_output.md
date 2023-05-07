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
# Warmup Iteration   1: 1.553 ops/ms
# Warmup Iteration   2: 3.797 ops/ms
# Warmup Iteration   3: 7.392 ops/ms
Iteration   1: 7.201 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.939 ±(99.9%) 11.715 ops/ms [Average]
  (min, avg, max) = (7.201, 7.939, 8.374), stdev = 0.642
  CI (99.9%): [≈ 0, 19.654] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.271 ops/ms
# Warmup Iteration   2: 6.950 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.372 ±(99.9%) 1.877 ops/ms [Average]
  (min, avg, max) = (8.259, 8.372, 8.461), stdev = 0.103
  CI (99.9%): [6.495, 10.249] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 6.701 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.265 ±(99.9%) 0.994 ops/ms [Average]
  (min, avg, max) = (8.222, 8.265, 8.326), stdev = 0.054
  CI (99.9%): [7.271, 9.258] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.753 ops/ms
# Warmup Iteration   3: 6.516 ops/ms
Iteration   1: 6.837 ops/ms
Iteration   2: 6.876 ops/ms
Iteration   3: 6.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.823 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (6.758, 6.823, 6.876), stdev = 0.060
  CI (99.9%): [5.724, 7.923] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 12.803 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
Iteration   3: 3.836 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.870 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.836, 3.870, 3.929), stdev = 0.051
  CI (99.9%): [2.931, 4.809] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.722 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.727 ±(99.9%) 0.006 ms/op
Iteration   2: 3.812 ±(99.9%) 0.004 ms/op
Iteration   3: 3.840 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.793 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.727, 3.793, 3.840), stdev = 0.059
  CI (99.9%): [2.720, 4.867] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.794 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.007 ms/op
Iteration   1: 4.002 ±(99.9%) 0.004 ms/op
Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
Iteration   3: 4.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.994 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.949, 3.994, 4.030), stdev = 0.041
  CI (99.9%): [3.242, 4.746] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 13.931 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.600 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.014 ms/op
Iteration   1: 4.710 ±(99.9%) 0.007 ms/op
Iteration   2: 4.512 ±(99.9%) 0.013 ms/op
Iteration   3: 4.559 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.594 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (4.512, 4.594, 4.710), stdev = 0.104
  CI (99.9%): [2.703, 6.485] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.272 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.017 ms/op
Iteration   1: 4.087 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  23.668 ms/op
                 createUser·p0.9999: 26.548 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 28.088 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 4.139 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  27.485 ms/op
                 createUser·p0.9999: 30.417 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237613
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 162 
    [ 2.500,  5.000) = 222652 
    [ 5.000,  7.500) = 13197 
    [ 7.500, 10.000) = 1085 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     29.007 ms/op
     p(99.9990) =     31.166 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.393 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  11.176 ms/op
                 existUser·p0.9999: 31.775 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   2: 4.048 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  25.329 ms/op
                 existUser·p0.9999: 27.430 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.912 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 30.652 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242627
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 228873 
    [ 5.000,  7.500) = 12087 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     12.994 ms/op
     p(99.9900) =     30.728 ms/op
     p(99.9990) =     32.553 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 11.751 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.917 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  14.483 ms/op
                 getUser·p0.9999: 26.897 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 3.893 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  23.478 ms/op
                 getUser·p0.9999: 26.692 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.134 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  11.129 ms/op
                 getUser·p0.9999: 27.802 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246640
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 237038 
    [ 5.000,  7.500) = 7914 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 142 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.446 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     28.119 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 15.170 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.517 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.017 ms/op
Iteration   1: 4.664 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  25.114 ms/op
                 listUser·p0.9999: 28.410 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 4.782 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  17.568 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 4.713 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  19.271 ms/op
                 listUser·p0.9999: 26.025 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203306
  mean =      4.719 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 169822 
    [ 5.000,  7.500) = 29707 
    [ 7.500, 10.000) = 2317 
    [10.000, 12.500) = 773 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     27.766 ms/op
     p(99.9990) =     29.850 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.939 ± 11.715  ops/ms
ClientPb.existUser                       thrpt       3   8.372 ±  1.877  ops/ms
ClientPb.getUser                         thrpt       3   8.265 ±  0.994  ops/ms
ClientPb.listUser                        thrpt       3   6.823 ±  1.099  ops/ms
ClientPb.createUser                       avgt       3   3.870 ±  0.939   ms/op
ClientPb.existUser                        avgt       3   3.793 ±  1.074   ms/op
ClientPb.getUser                          avgt       3   3.994 ±  0.752   ms/op
ClientPb.listUser                         avgt       3   4.594 ±  1.891   ms/op
ClientPb.createUser                     sample  237613   4.040 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.574            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.145            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.849            ms/op
ClientPb.createUser:createUser·p0.999   sample          23.691            ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.007            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.244            ms/op
ClientPb.existUser                      sample  242627   3.954 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.495            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.809            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.653            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.079            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.873            ms/op
ClientPb.existUser:existUser·p0.999     sample          12.994            ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.728            ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554            ms/op
ClientPb.getUser                        sample  246640   3.891 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.100            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.731            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.350            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.849            ms/op
ClientPb.getUser:getUser·p0.999         sample          14.446            ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.394            ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687            ms/op
ClientPb.listUser                       sample  203306   4.719 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.964            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.595            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.929            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.463            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.766            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539            ms/op
